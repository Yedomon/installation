# Installation


### Pac-Bio Hifi assemblers

#### Hi-canu


Update System

Firstly we need to update the system through yum update command as shown below.

```bash

$ sudo yum update

```

Install Perl Package
Once System is fully updated, you can install perl package through yum install perl command as shown below.


```bash

$ sudo yum install perl

```

Check

```bash

$ perl -v


```

Should get this info

```bash
This is perl 5, version 16, subversion 3 (v5.16.3) built for x86_64-linux-thread-multi
(with 44 registered patches, see perl -V for more detail)

Copyright 1987-2012, Larry Wall

Perl may be copied only under the terms of either the Artistic License or the
GNU General Public License, which may be found in the Perl 5 source kit.

Complete documentation for Perl, including FAQ lists, should be found on
this system using "man perl" or "perldoc perl".  If you have access to the
Internet, point your browser at http://www.perl.org/, the Perl Home Page.


```

Install java

```bash

$ sudo yum install java-1.8.0-openjdk


```

Check


```bash

$ java -version

```


Should see this info



```bash

openjdk version "1.8.0_282"
OpenJDK Runtime Environment (build 1.8.0_282-b08)
OpenJDK 64-Bit Server VM (build 25.282-b08, mixed mode)

```

The easy way to install canu is to download the hicanu binary

```bash
 
$ wget https://github.com/marbl/canu/releases/download/v2.1.1/canu-2.1.1.Linux-amd64.tar.xz

```



Install from binary distribution


```bash

tar -xJf canu-2.1.1.Linux-amd64.tar.xz

```

Done! canu is well installed and available here

```bash

cd canu-2.1.1/bin

```


Check


```bash

./canu

```



Should get this

```bash


usage:   canu [-version] [-citation] \
              [-haplotype | -correct | -trim | -assemble | -trim-assemble] \
              [-s <assembly-specifications-file>] \
               -p <assembly-prefix> \
               -d <assembly-directory> \
               genomeSize=<number>[g|m|k] \
              [other-options] \
              [-haplotype{NAME} illumina.fastq.gz] \
              [-corrected] \
              [-trimmed] \
              [-pacbio |
               -nanopore |
               -pacbio-hifi] file1 file2 ...

example: canu -d run1 -p godzilla genomeSize=1g -nanopore-raw reads/*.fasta.gz


  To restrict canu to only a specific stage, use:
    -haplotype     - generate haplotype-specific reads
    -correct       - generate corrected reads
    -trim          - generate trimmed reads
    -assemble      - generate an assembly
    -trim-assemble - generate trimmed reads and then assemble them

  The assembly is computed in the -d <assembly-directory>, with output files named
  using the -p <assembly-prefix>.  This directory is created if needed.  It is not
  possible to run multiple assemblies in the same directory.

  The genome size should be your best guess of the haploid genome size of what is being
  assembled.  It is used primarily to estimate coverage in reads, NOT as the desired
  assembly size.  Fractional values are allowed: '4.7m' equals '4700k' equals '4700000'

  Some common options:
    useGrid=string
      - Run under grid control (true), locally (false), or set up for grid control
        but don't submit any jobs (remote)
    rawErrorRate=fraction-error
      - The allowed difference in an overlap between two raw uncorrected reads.  For lower
        quality reads, use a higher number.  The defaults are 0.300 for PacBio reads and
        0.500 for Nanopore reads.
    correctedErrorRate=fraction-error
      - The allowed difference in an overlap between two corrected reads.  Assemblies of
        low coverage or data with biological differences will benefit from a slight increase
        in this.  Defaults are 0.045 for PacBio reads and 0.144 for Nanopore reads.
    gridOptions=string
      - Pass string to the command used to submit jobs to the grid.  Can be used to set
        maximum run time limits.  Should NOT be used to set memory limits; Canu will do
        that for you.
    minReadLength=number
      - Ignore reads shorter than 'number' bases long.  Default: 1000.
    minOverlapLength=number
      - Ignore read-to-read overlaps shorter than 'number' bases long.  Default: 500.
  A full list of options can be printed with '-options'.  All options can be supplied in
  an optional sepc file with the -s option.

  For TrioCanu, haplotypes are specified with the -haplotype{NAME} option, with any
  number of haplotype-specific Illumina read files after.  The {NAME} of each haplotype
  is free text (but only letters and numbers, please).  For example:
    -haplotypeNANNY nanny/*gz
    -haplotypeBILLY billy1.fasta.gz billy2.fasta.gz

  Reads can be either FASTA or FASTQ format, uncompressed, or compressed with gz, bz2 or xz.

  Reads are specified by the technology they were generated with, and any processing performed.

  [processing]
    -corrected
    -trimmed

  [technology]
    -pacbio      <files>
    -nanopore    <files>
    -pacbio-hifi <files>

Complete documentation at http://canu.readthedocs.org/en/latest/

```



