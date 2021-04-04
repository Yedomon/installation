# Installation
##Install gblocks

wget http://molevol.cmima.csic.es/castresana/Gblocks/Gblocks_Linux64_0.91b.tar.Z

tar zxvf Gblocks_Linux_0.91b.tar.Z
















### Miniconda3 














Step 1: Download latest conda installer


```python

$ wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh


```



Log info



```

--2021-02-12 18:18:56--  https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
Resolving repo.continuum.io (repo.continuum.io)... 104.18.200.79, 104.18.201.79, 2606:4700::6812:c94f, ...
Connecting to repo.continuum.io (repo.continuum.io)|104.18.200.79|:443... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh [following]
--2021-02-12 18:18:56--  https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
Resolving repo.anaconda.com (repo.anaconda.com)... 104.16.131.3, 104.16.130.3, 2606:4700::6810:8203, ...
Connecting to repo.anaconda.com (repo.anaconda.com)|104.16.131.3|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 94235922 (90M) [application/x-sh]
Saving to: ‘Miniconda3-latest-Linux-x86_64.sh’

100%[=====================================================================================================================================================================>] 94,235,922  51.0MB/s   in 1.8s

2021-02-12 18:18:58 (51.0 MB/s) - ‘Miniconda3-latest-Linux-x86_64.sh’ saved [94235922/94235922]

```


Step 2: Run the installer


```python

$ bash Miniconda3-latest-Linux-x86_64.sh


```

Log info

```

Welcome to Miniconda3 py38_4.9.2

In order to continue the installation process, please review the license
agreement.
Please, press ENTER to continue
>>>


```
Press ENTER untill this message appear


```

Do you accept the license terms? [yes|no]


```


Type *yes*



Log info


```

Miniconda3 will now be installed into this location:
/home/kplee/miniconda3

  - Press ENTER to confirm the location
  - Press CTRL-C to abort the installation
  - Or specify a different location below

[/home/kplee/miniconda3] >>> /home/kplee/program/miniconda3


```

I set */home/kplee/program/miniconda3* as the installation path and press *ENTER*



Log info

```
PREFIX=/home/kplee/program/miniconda3
Unpacking payload ...
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /home/kplee/program/miniconda3

  added / updated specs:
    - _libgcc_mutex==0.1=main
    - brotlipy==0.7.0=py38h27cfd23_1003
    - ca-certificates==2020.10.14=0
    - certifi==2020.6.20=pyhd3eb1b0_3
    - cffi==1.14.3=py38h261ae71_2
    - chardet==3.0.4=py38h06a4308_1003
    - conda-package-handling==1.7.2=py38h03888b9_0
    - conda==4.9.2=py38h06a4308_0
    - cryptography==3.2.1=py38h3c74f83_1
    - idna==2.10=py_0
    - ld_impl_linux-64==2.33.1=h53a641e_7
    - libedit==3.1.20191231=h14c3975_1
    - libffi==3.3=he6710b0_2
    - libgcc-ng==9.1.0=hdf63c60_0
    - libstdcxx-ng==9.1.0=hdf63c60_0
    - ncurses==6.2=he6710b0_1
    - openssl==1.1.1h=h7b6447c_0
    - pip==20.2.4=py38h06a4308_0
    - pycosat==0.6.3=py38h7b6447c_1
    - pycparser==2.20=py_2
    - pyopenssl==19.1.0=pyhd3eb1b0_1
    - pysocks==1.7.1=py38h06a4308_0
    - python==3.8.5=h7579374_1
    - readline==8.0=h7b6447c_0
    - requests==2.24.0=py_0
    - ruamel_yaml==0.15.87=py38h7b6447c_1
    - setuptools==50.3.1=py38h06a4308_1
    - six==1.15.0=py38h06a4308_0
    - sqlite==3.33.0=h62c20be_0
    - tk==8.6.10=hbc83047_0
    - tqdm==4.51.0=pyhd3eb1b0_0
    - urllib3==1.25.11=py_0
    - wheel==0.35.1=pyhd3eb1b0_0
    - xz==5.2.5=h7b6447c_0
    - yaml==0.2.5=h7b6447c_0
    - zlib==1.2.11=h7b6447c_3


The following NEW packages will be INSTALLED:

  _libgcc_mutex      pkgs/main/linux-64::_libgcc_mutex-0.1-main
  brotlipy           pkgs/main/linux-64::brotlipy-0.7.0-py38h27cfd23_1003
  ca-certificates    pkgs/main/linux-64::ca-certificates-2020.10.14-0
  certifi            pkgs/main/noarch::certifi-2020.6.20-pyhd3eb1b0_3
  cffi               pkgs/main/linux-64::cffi-1.14.3-py38h261ae71_2
  chardet            pkgs/main/linux-64::chardet-3.0.4-py38h06a4308_1003
  conda              pkgs/main/linux-64::conda-4.9.2-py38h06a4308_0
  conda-package-han~ pkgs/main/linux-64::conda-package-handling-1.7.2-py38h03888b9_0
  cryptography       pkgs/main/linux-64::cryptography-3.2.1-py38h3c74f83_1
  idna               pkgs/main/noarch::idna-2.10-py_0
  ld_impl_linux-64   pkgs/main/linux-64::ld_impl_linux-64-2.33.1-h53a641e_7
  libedit            pkgs/main/linux-64::libedit-3.1.20191231-h14c3975_1
  libffi             pkgs/main/linux-64::libffi-3.3-he6710b0_2
  libgcc-ng          pkgs/main/linux-64::libgcc-ng-9.1.0-hdf63c60_0
  libstdcxx-ng       pkgs/main/linux-64::libstdcxx-ng-9.1.0-hdf63c60_0
  ncurses            pkgs/main/linux-64::ncurses-6.2-he6710b0_1
  openssl            pkgs/main/linux-64::openssl-1.1.1h-h7b6447c_0
  pip                pkgs/main/linux-64::pip-20.2.4-py38h06a4308_0
  pycosat            pkgs/main/linux-64::pycosat-0.6.3-py38h7b6447c_1
  pycparser          pkgs/main/noarch::pycparser-2.20-py_2
  pyopenssl          pkgs/main/noarch::pyopenssl-19.1.0-pyhd3eb1b0_1
  pysocks            pkgs/main/linux-64::pysocks-1.7.1-py38h06a4308_0
  python             pkgs/main/linux-64::python-3.8.5-h7579374_1
  readline           pkgs/main/linux-64::readline-8.0-h7b6447c_0
  requests           pkgs/main/noarch::requests-2.24.0-py_0
  ruamel_yaml        pkgs/main/linux-64::ruamel_yaml-0.15.87-py38h7b6447c_1
  setuptools         pkgs/main/linux-64::setuptools-50.3.1-py38h06a4308_1
  six                pkgs/main/linux-64::six-1.15.0-py38h06a4308_0
  sqlite             pkgs/main/linux-64::sqlite-3.33.0-h62c20be_0
  tk                 pkgs/main/linux-64::tk-8.6.10-hbc83047_0
  tqdm               pkgs/main/noarch::tqdm-4.51.0-pyhd3eb1b0_0
  urllib3            pkgs/main/noarch::urllib3-1.25.11-py_0
  wheel              pkgs/main/noarch::wheel-0.35.1-pyhd3eb1b0_0
  xz                 pkgs/main/linux-64::xz-5.2.5-h7b6447c_0
  yaml               pkgs/main/linux-64::yaml-0.2.5-h7b6447c_0
  zlib               pkgs/main/linux-64::zlib-1.2.11-h7b6447c_3


Preparing transaction: done
Executing transaction: done
installation finished.
Do you wish the installer to initialize Miniconda3
by running conda init? [yes|no]
[no] >>>

```


I typed *yes*


Log info


```
no change     /home/kplee/program/miniconda3/condabin/conda
no change     /home/kplee/program/miniconda3/bin/conda
no change     /home/kplee/program/miniconda3/bin/conda-env
no change     /home/kplee/program/miniconda3/bin/activate
no change     /home/kplee/program/miniconda3/bin/deactivate
no change     /home/kplee/program/miniconda3/etc/profile.d/conda.sh
no change     /home/kplee/program/miniconda3/etc/fish/conf.d/conda.fish
no change     /home/kplee/program/miniconda3/shell/condabin/Conda.psm1
no change     /home/kplee/program/miniconda3/shell/condabin/conda-hook.ps1
no change     /home/kplee/program/miniconda3/lib/python3.8/site-packages/xontrib/conda.xsh
no change     /home/kplee/program/miniconda3/etc/profile.d/conda.csh
modified      /home/kplee/.bashrc

==> For changes to take effect, close and re-open your current shell. <==

If you'd prefer that conda's base environment not be activated on startup,
   set the auto_activate_base parameter to false:

conda config --set auto_activate_base false

Thank you for installing Miniconda3!


```

Please close and reopen the terminal, to complete the installation.

After closing and re-opening the shell/terminal, we should be able to use the conda command:


```python

$ conda update --yes conda

```


Log info


```
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /home/kplee/program/miniconda3

  added / updated specs:
    - conda


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    _openmp_mutex-4.5          |            1_gnu          22 KB
    ca-certificates-2021.1.19  |       h06a4308_0         121 KB
    certifi-2020.12.5          |   py38h06a4308_0         141 KB
    cffi-1.14.4                |   py38h261ae71_0         226 KB
    chardet-4.0.0              |py38h06a4308_1003         194 KB
    cryptography-3.3.1         |   py38h3c74f83_0         566 KB
    idna-2.10                  |     pyhd3eb1b0_0          52 KB
    ld_impl_linux-64-2.35.1    |       h2b15070_1         627 KB
    libgcc-ng-9.3.0            |      h9cbead1_17         7.8 MB
    libgomp-9.3.0              |      h9cbead1_17         377 KB
    libstdcxx-ng-9.3.0         |      h2ae2ef3_17         4.0 MB
    openssl-1.1.1i             |       h27cfd23_0         2.5 MB
    pip-20.3.3                 |   py38h06a4308_0         1.8 MB
    pyopenssl-20.0.1           |     pyhd3eb1b0_1          49 KB
    readline-8.1               |       h27cfd23_0         362 KB
    requests-2.25.1            |     pyhd3eb1b0_0          52 KB
    setuptools-52.0.0          |   py38h06a4308_0         714 KB
    tqdm-4.56.0                |     pyhd3eb1b0_0          80 KB
    urllib3-1.26.3             |     pyhd3eb1b0_0         105 KB
    wheel-0.36.2               |     pyhd3eb1b0_0          33 KB
    ------------------------------------------------------------
                                           Total:        19.8 MB

The following NEW packages will be INSTALLED:

  _openmp_mutex      pkgs/main/linux-64::_openmp_mutex-4.5-1_gnu
  libgomp            pkgs/main/linux-64::libgomp-9.3.0-h9cbead1_17

The following packages will be UPDATED:

  ca-certificates                              2020.10.14-0 --> 2021.1.19-h06a4308_0
  certifi            pkgs/main/noarch::certifi-2020.6.20-p~ --> pkgs/main/linux-64::certifi-2020.12.5-py38h06a4308_0
  cffi                                1.14.3-py38h261ae71_2 --> 1.14.4-py38h261ae71_0
  chardet                           3.0.4-py38h06a4308_1003 --> 4.0.0-py38h06a4308_1003
  cryptography                         3.2.1-py38h3c74f83_1 --> 3.3.1-py38h3c74f83_0
  ld_impl_linux-64                        2.33.1-h53a641e_7 --> 2.35.1-h2b15070_1
  libgcc-ng                                9.1.0-hdf63c60_0 --> 9.3.0-h9cbead1_17
  libstdcxx-ng                             9.1.0-hdf63c60_0 --> 9.3.0-h2ae2ef3_17
  openssl                                 1.1.1h-h7b6447c_0 --> 1.1.1i-h27cfd23_0
  pip                                 20.2.4-py38h06a4308_0 --> 20.3.3-py38h06a4308_0
  pyopenssl                             19.1.0-pyhd3eb1b0_1 --> 20.0.1-pyhd3eb1b0_1
  readline                                   8.0-h7b6447c_0 --> 8.1-h27cfd23_0
  requests                                      2.24.0-py_0 --> 2.25.1-pyhd3eb1b0_0
  setuptools                          50.3.1-py38h06a4308_1 --> 52.0.0-py38h06a4308_0
  tqdm                                  4.51.0-pyhd3eb1b0_0 --> 4.56.0-pyhd3eb1b0_0
  urllib3                                      1.25.11-py_0 --> 1.26.3-pyhd3eb1b0_0
  wheel                                 0.35.1-pyhd3eb1b0_0 --> 0.36.2-pyhd3eb1b0_0

The following packages will be DOWNGRADED:

  idna                                            2.10-py_0 --> 2.10-pyhd3eb1b0_0



Downloading and Extracting Packages
tqdm-4.56.0          | 80 KB     | #################################################################################################################################################################### | 100%
libgomp-9.3.0        | 377 KB    | #################################################################################################################################################################### | 100%
pyopenssl-20.0.1     | 49 KB     | #################################################################################################################################################################### | 100%
chardet-4.0.0        | 194 KB    | #################################################################################################################################################################### | 100%
cryptography-3.3.1   | 566 KB    | #################################################################################################################################################################### | 100%
cffi-1.14.4          | 226 KB    | #################################################################################################################################################################### | 100%
libgcc-ng-9.3.0      | 7.8 MB    | #################################################################################################################################################################### | 100%
ld_impl_linux-64-2.3 | 627 KB    | #################################################################################################################################################################### | 100%
certifi-2020.12.5    | 141 KB    | #################################################################################################################################################################### | 100%
requests-2.25.1      | 52 KB     | #################################################################################################################################################################### | 100%
ca-certificates-2021 | 121 KB    | #################################################################################################################################################################### | 100%
_openmp_mutex-4.5    | 22 KB     | #################################################################################################################################################################### | 100%
readline-8.1         | 362 KB    | #################################################################################################################################################################### | 100%
openssl-1.1.1i       | 2.5 MB    | #################################################################################################################################################################### | 100%
pip-20.3.3           | 1.8 MB    | #################################################################################################################################################################### | 100%
urllib3-1.26.3       | 105 KB    | #################################################################################################################################################################### | 100%
libstdcxx-ng-9.3.0   | 4.0 MB    | #################################################################################################################################################################### | 100%
idna-2.10            | 52 KB     | #################################################################################################################################################################### | 100%
wheel-0.36.2         | 33 KB     | #################################################################################################################################################################### | 100%
setuptools-52.0.0    | 714 KB    | #################################################################################################################################################################### | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: done


```



Step 4: Installing conda channels to make tools available
Different tools are packaged in what conda calls channels. We need to add some channels to make the bioinformatics and genomics tools available for installation:

```python
# Install some conda channels
# A channel is where conda looks for packages
$ conda config --add channels defaults
$ conda config --add channels bioconda
$ conda config --add channels conda-forge

```

Attention

The order of adding channels is important. Make sure you use the shown order of commands.








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


### Flye


First install python3



```bash

sudo yum install python3-devel

```


clone the repository and compile



```bash

sudo git clone https://github.com/fenderglass/Flye

cd Flye

sudo make

```


Check


```bash

./flye -h


```


Should see:


```bash

usage: flye (--pacbio-raw | --pacbio-corr | --pacbio-hifi | --nano-raw |
             --nano-corr | --subassemblies) file1 [file_2 ...]
             --out-dir PATH

             [--genome-size SIZE] [--threads int] [--iterations int]
             [--meta] [--plasmids] [--trestle] [--polish-target]
             [--keep-haplotypes] [--debug] [--version] [--help]
             [--resume] [--resume-from] [--stop-after]
             [--hifi-error] [--min-overlap SIZE]

Assembly of long reads with repeat graphs

optional arguments:
  -h, --help            show this help message and exit
  --pacbio-raw path [path ...]
                        PacBio raw reads
  --pacbio-corr path [path ...]
                        PacBio corrected reads
  --pacbio-hifi path [path ...]
                        PacBio HiFi reads
  --nano-raw path [path ...]
                        ONT raw reads
  --nano-corr path [path ...]
                        ONT corrected reads
  --subassemblies path [path ...]
                        high-quality contigs input
  -g size, --genome-size size
                        estimated genome size (for example, 5m or 2.6g)
  -o path, --out-dir path
                        Output directory
  -t int, --threads int
                        number of parallel threads [1]
  -i int, --iterations int
                        number of polishing iterations [1]
  -m int, --min-overlap int
                        minimum overlap between reads [auto]
  --asm-coverage int    reduced coverage for initial disjointig assembly [not
                        set]
  --hifi-error float    expected HiFi reads error rate (e.g. 0.01 or 0.001)
                        [0.01]
  --plasmids            rescue short unassembled plasmids
  --meta                metagenome / uneven coverage mode
  --keep-haplotypes     do not collapse alternative haplotypes
  --trestle             enable Trestle [disabled]
  --polish-target path  run polisher on the target sequence
  --resume              resume from the last completed stage
  --resume-from stage_name
                        resume from a custom stage
  --stop-after stage_name
                        stop after the specified stage completed
  --debug               enable debug output
  -v, --version         show program's version number and exit

Input reads can be in FASTA or FASTQ format, uncompressed
or compressed with gz. Currently, PacBio (raw, corrected, HiFi)
and ONT reads (raw, corrected) are supported. Expected error rates are
<30% for raw, <3% for corrected, and <1% for HiFi. Note that Flye
was primarily developed to run on raw reads. Additionally, the
--subassemblies option performs a consensus assembly of multiple
sets of high-quality contigs. You may specify multiple
files with reads (separated by spaces). Mixing different read
types is not yet supported. The --meta option enables the mode
for metagenome/uneven coverage assembly.

Genome size estimate is no longer a required option. You
need to provide an estimate if using --asm-coverage option.

To reduce memory consumption for large genome assemblies,
you can use a subset of the longest reads for initial disjointig
assembly by specifying --asm-coverage and --genome-size options. Typically,
40x coverage is enough to produce good disjointigs.

You can run Flye polisher as a standalone tool using
--polish-target option.


```


Fine! Flye is installed. 



### Hifiasm


Just do:


```bash

$ sudo git clone https://github.com/chhylp123/hifiasm

$ cd hifiasm && make

```




### Install the conda package manager


```bash

# download latest conda installer
$ wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh

```

Now lets install conda:


```bash

# run the installer
$ bash Miniconda3-latest-Linux-x86_64.sh

```


Accept the license



```bash


Do you accept the license terms? [yes|no]


```



Press `Yes`


After you accepted the license agreement conda will be installed. At the end of the installation you will encounter the following:

```bash

Preparing transaction: done
Executing transaction: done
installation finished.
Do you wish the installer to initialize Miniconda3
by running conda init? [yes|no]


```


Should see the last info


```bash



no change     /home/kplee/miniconda3/condabin/conda
no change     /home/kplee/miniconda3/bin/conda
no change     /home/kplee/miniconda3/bin/conda-env
no change     /home/kplee/miniconda3/bin/activate
no change     /home/kplee/miniconda3/bin/deactivate
no change     /home/kplee/miniconda3/etc/profile.d/conda.sh
no change     /home/kplee/miniconda3/etc/fish/conf.d/conda.fish
no change     /home/kplee/miniconda3/shell/condabin/Conda.psm1
no change     /home/kplee/miniconda3/shell/condabin/conda-hook.ps1
no change     /home/kplee/miniconda3/lib/python3.8/site-packages/xontrib/conda.xsh
no change     /home/kplee/miniconda3/etc/profile.d/conda.csh
modified      /home/kplee/.bashrc

==> For changes to take effect, close and re-open your current shell. <==

If you'd prefer that conda's base environment not be activated on startup,
   set the auto_activate_base parameter to false:

conda config --set auto_activate_base false

Thank you for installing Miniconda3!


```



close and open the terminal



After closing and re-opening the shell/terminal, we should be able to use the conda command:



```bash

$ conda update --yes conda


```

Installing conda channels to make tools available

```bash


# Install some conda channels
# A channel is where conda looks for packages
$ conda config --add channels defaults
$ conda config --add channels bioconda
$ conda config --add channels conda-forge


```

### Peregrine

Upgrade the gcc


```python


$ yum -y install centos-release-scl
$ yum -y install devtoolset-7-gcc devtoolset-7-gcc-c++ devtoolset-7-binutils
$ scl enable devtoolset-7 bash


```

Check




```python

gcc -v

```
get this:


```python

Using built-in specs.
COLLECT_GCC=gcc
COLLECT_LTO_WRAPPER=/opt/rh/devtoolset-7/root/usr/libexec/gcc/x86_64-redhat-linux/7/lto-wrapper
Target: x86_64-redhat-linux
Configured with: ../configure --enable-bootstrap --enable-languages=c,c++,fortran,lto --prefix=/opt/rh/devtoolset-7/root/usr --mandir=/opt/rh/devtoolset-7/root/usr/share/man --infodir=/opt/rh/devtoolset-7/root/usr/share/info --with-bugurl=http://bugzilla.redhat.com/bugzilla --enable-shared --enable-threads=posix --enable-checking=release --enable-multilib --with-system-zlib --enable-__cxa_atexit --disable-libunwind-exceptions --enable-gnu-unique-object --enable-linker-build-id --with-gcc-major-version-only --enable-plugin --with-linker-hash-style=gnu --enable-initfini-array --with-default-libstdcxx-abi=gcc4-compatible --with-isl=/builddir/build/BUILD/gcc-7.3.1-20180303/obj-x86_64-redhat-linux/isl-install --enable-libmpx --enable-gnu-indirect-function --with-tune=generic --with-arch_32=i686 --build=x86_64-redhat-linux
Thread model: posix
gcc version 7.3.1 20180303 (Red Hat 7.3.1-5) (GCC)



````


Download and install via conda

```python

git clone https://github.com/cschin/Peregrine.git

cd Peregrine

bash install_with_conda.sh

```


Note: 
I modified the sh file by replacing `. ~/miniconda3/bin/activate` by `. ~/anaconda3/bin/activate`



### Improved Phased Assembly HiFi Genome Assembler


```python

conda create -n ipa
conda activate ipa
conda install pbipa

```

Run on data

```python

/usr/bin/time -o out.ram.txt -v ipa local --nthreads 16 --njobs 2 -i ~/datafile/001.i.bat.pacbio.hifi.reads/S_unknown.ccs.merged.fasta &> log &

```



# Docker installation


Step 1: Uninstall old versions
Older versions of Docker were called docker or docker-engine. If these are installed, uninstall them, along with associated dependencies.


```python

$ sudo yum remove docker \
                  docker-client \
                  docker-client-latest \
                  docker-common \
                  docker-latest \
                  docker-latest-logrotate \
                  docker-logrotate \
                  docker-engine
                  
```

Log info

```
Loaded plugins: fastestmirror
No Match for argument: docker
No Match for argument: docker-client
No Match for argument: docker-client-latest
No Match for argument: docker-common
No Match for argument: docker-latest
No Match for argument: docker-latest-logrotate
No Match for argument: docker-logrotate
No Match for argument: docker-engine
No Packages marked for removal


```



Step 2: Install using the repository

Before you install Docker Engine for the first time on a new host machine, you need to set up the Docker repository. Afterward, you can install and update Docker from the repository.


Step 2.1: Install dependencies

The next step is to download the dependencies required for installing Docker.

Type in the following command:


```python

sudo yum install -y yum-utils device-mapper-persistent-data lvm2

```


Log info:

```
Loaded plugins: fastestmirror
Loading mirror speeds from cached hostfile
 * base: mirror.kakao.com
 * extras: mirror.kakao.com
 * updates: mirror.kakao.com
base                                                                                                                                                                                    | 3.6 kB  00:00:00
extras                                                                                                                                                                                  | 2.9 kB  00:00:00
updates                                                                                                                                                                                 | 2.9 kB  00:00:00
Package device-mapper-persistent-data-0.8.5-3.el7_9.2.x86_64 already installed and latest version
Package 7:lvm2-2.02.187-6.el7_9.3.x86_64 already installed and latest version
Resolving Dependencies
--> Running transaction check
---> Package yum-utils.noarch 0:1.1.31-54.el7_8 will be installed
--> Processing Dependency: python-kitchen for package: yum-utils-1.1.31-54.el7_8.noarch
--> Processing Dependency: libxml2-python for package: yum-utils-1.1.31-54.el7_8.noarch
--> Running transaction check
---> Package libxml2-python.x86_64 0:2.9.1-6.el7.5 will be installed
---> Package python-kitchen.noarch 0:1.1.1-5.el7 will be installed
--> Processing Dependency: python-chardet for package: python-kitchen-1.1.1-5.el7.noarch
--> Running transaction check
---> Package python-chardet.noarch 0:2.2.1-3.el7 will be installed
--> Finished Dependency Resolution

Dependencies Resolved

===============================================================================================================================================================================================================
 Package                                               Arch                                          Version                                                 Repository                                   Size
===============================================================================================================================================================================================================
Installing:
 yum-utils                                             noarch                                        1.1.31-54.el7_8                                         base                                        122 k
Installing for dependencies:
 libxml2-python                                        x86_64                                        2.9.1-6.el7.5                                           base                                        247 k
 python-chardet                                        noarch                                        2.2.1-3.el7                                             base                                        227 k
 python-kitchen                                        noarch                                        1.1.1-5.el7                                             base                                        267 k

Transaction Summary
===============================================================================================================================================================================================================
Install  1 Package (+3 Dependent packages)

Total download size: 863 k
Installed size: 4.3 M
Downloading packages:
(1/4): libxml2-python-2.9.1-6.el7.5.x86_64.rpm                                                                                                                                          | 247 kB  00:00:00
(2/4): python-chardet-2.2.1-3.el7.noarch.rpm                                                                                                                                            | 227 kB  00:00:00
(3/4): yum-utils-1.1.31-54.el7_8.noarch.rpm                                                                                                                                             | 122 kB  00:00:00
(4/4): python-kitchen-1.1.1-5.el7.noarch.rpm                                                                                                                                            | 267 kB  00:00:00
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Total                                                                                                                                                                          1.7 MB/s | 863 kB  00:00:00
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  Installing : python-chardet-2.2.1-3.el7.noarch                                                                                                                                                           1/4
  Installing : python-kitchen-1.1.1-5.el7.noarch                                                                                                                                                           2/4
  Installing : libxml2-python-2.9.1-6.el7.5.x86_64                                                                                                                                                         3/4
  Installing : yum-utils-1.1.31-54.el7_8.noarch                                                                                                                                                            4/4
  Verifying  : libxml2-python-2.9.1-6.el7.5.x86_64                                                                                                                                                         1/4
  Verifying  : python-kitchen-1.1.1-5.el7.noarch                                                                                                                                                           2/4
  Verifying  : yum-utils-1.1.31-54.el7_8.noarch                                                                                                                                                            3/4
  Verifying  : python-chardet-2.2.1-3.el7.noarch                                                                                                                                                           4/4

Installed:
  yum-utils.noarch 0:1.1.31-54.el7_8

Dependency Installed:
  libxml2-python.x86_64 0:2.9.1-6.el7.5                                 python-chardet.noarch 0:2.2.1-3.el7                                 python-kitchen.noarch 0:1.1.1-5.el7

Complete!

```





The –y switch indicates to the yum installer to answer “yes” to any prompts that may come up. The yum-utils switch adds the yum-config-manager. Docker uses a device mapper storage driver, and the device-mapper-persistent-data and lvm2 packages are required for it to run correctly.


Step 2.2: Add the Docker Repository to CentOS

```python

$ sudo yum-config-manager \
    --add-repo \
    https://download.docker.com/linux/centos/docker-ce.repo
    
    
```

Log info


```
Loaded plugins: fastestmirror
adding repo from: https://download.docker.com/linux/centos/docker-ce.repo
grabbing file https://download.docker.com/linux/centos/docker-ce.repo to /etc/yum.repos.d/docker-ce.repo
repo saved to /etc/yum.repos.d/docker-ce.repo

```

Step 3: Install the latest version of Docker Engine and containerd


```python

$ sudo yum install docker-ce docker-ce-cli containerd.io


```


Log info


```
Resolving Dependencies
--> Running transaction check
---> Package containerd.io.x86_64 0:1.4.3-3.1.el7 will be installed
--> Processing Dependency: container-selinux >= 2:2.74 for package: containerd.io-1.4.3-3.1.el7.x86_64
--> Processing Dependency: libseccomp for package: containerd.io-1.4.3-3.1.el7.x86_64
---> Package docker-ce.x86_64 3:20.10.3-3.el7 will be installed
--> Processing Dependency: docker-ce-rootless-extras for package: 3:docker-ce-20.10.3-3.el7.x86_64
---> Package docker-ce-cli.x86_64 1:20.10.3-3.el7 will be installed
--> Running transaction check
---> Package container-selinux.noarch 2:2.119.2-1.911c772.el7_8 will be installed
---> Package docker-ce-rootless-extras.x86_64 0:20.10.3-3.el7 will be installed
--> Processing Dependency: fuse-overlayfs >= 0.7 for package: docker-ce-rootless-extras-20.10.3-3.el7.x86_64
--> Processing Dependency: slirp4netns >= 0.4 for package: docker-ce-rootless-extras-20.10.3-3.el7.x86_64
---> Package libseccomp.x86_64 0:2.3.1-4.el7 will be installed
--> Running transaction check
---> Package fuse-overlayfs.x86_64 0:0.7.2-6.el7_8 will be installed
--> Processing Dependency: libfuse3.so.3(FUSE_3.2)(64bit) for package: fuse-overlayfs-0.7.2-6.el7_8.x86_64
--> Processing Dependency: libfuse3.so.3(FUSE_3.0)(64bit) for package: fuse-overlayfs-0.7.2-6.el7_8.x86_64
--> Processing Dependency: libfuse3.so.3()(64bit) for package: fuse-overlayfs-0.7.2-6.el7_8.x86_64
---> Package slirp4netns.x86_64 0:0.4.3-4.el7_8 will be installed
--> Running transaction check
---> Package fuse3-libs.x86_64 0:3.6.1-4.el7 will be installed
--> Finished Dependency Resolution

Dependencies Resolved

===============================================================================================================================================================================================================
 Package                                                  Arch                                  Version                                                  Repository                                       Size
===============================================================================================================================================================================================================
Installing:
 containerd.io                                            x86_64                                1.4.3-3.1.el7                                            docker-ce-stable                                 33 M
 docker-ce                                                x86_64                                3:20.10.3-3.el7                                          docker-ce-stable                                 27 M
 docker-ce-cli                                            x86_64                                1:20.10.3-3.el7                                          docker-ce-stable                                 33 M
Installing for dependencies:
 container-selinux                                        noarch                                2:2.119.2-1.911c772.el7_8                                extras                                           40 k
 docker-ce-rootless-extras                                x86_64                                20.10.3-3.el7                                            docker-ce-stable                                9.0 M
 fuse-overlayfs                                           x86_64                                0.7.2-6.el7_8                                            extras                                           54 k
 fuse3-libs                                               x86_64                                3.6.1-4.el7                                              extras                                           82 k
 libseccomp                                               x86_64                                2.3.1-4.el7                                              base                                             56 k
 slirp4netns                                              x86_64                                0.4.3-4.el7_8                                            extras                                           81 k

Transaction Summary
===============================================================================================================================================================================================================
Install  3 Packages (+6 Dependent packages)

Total download size: 102 M
Installed size: 423 M


```

Type *y* to allow the operation to complete.


log info


```
Downloading packages:
(1/9): container-selinux-2.119.2-1.911c772.el7_8.noarch.rpm                                                                                                                             |  40 kB  00:00:00
warning: /var/cache/yum/x86_64/7/docker-ce-stable/packages/containerd.io-1.4.3-3.1.el7.x86_64.rpm: Header V4 RSA/SHA512 Signature, key ID 621e9f35: NOKEY                    ]  20 MB/s |  18 MB  00:00:04 ETA
Public key for containerd.io-1.4.3-3.1.el7.x86_64.rpm is not installed
(2/9): containerd.io-1.4.3-3.1.el7.x86_64.rpm                                                                                                                                           |  33 MB  00:00:01
(3/9): docker-ce-cli-20.10.3-3.el7.x86_64.rpm                                                                                                                                           |  33 MB  00:00:00
(4/9): docker-ce-20.10.3-3.el7.x86_64.rpm                                                                                                                                               |  27 MB  00:00:02
(5/9): fuse-overlayfs-0.7.2-6.el7_8.x86_64.rpm                                                                                                                                          |  54 kB  00:00:00
(6/9): libseccomp-2.3.1-4.el7.x86_64.rpm                                                                                                                                                |  56 kB  00:00:00
(7/9): docker-ce-rootless-extras-20.10.3-3.el7.x86_64.rpm                                                                                                                               | 9.0 MB  00:00:00
(8/9): slirp4netns-0.4.3-4.el7_8.x86_64.rpm                                                                                                                                             |  81 kB  00:00:00
(9/9): fuse3-libs-3.6.1-4.el7.x86_64.rpm                                                                                                                                                |  82 kB  00:00:00
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Total                                                                                                                                                                           39 MB/s | 102 MB  00:00:02
Retrieving key from https://download.docker.com/linux/centos/gpg
Importing GPG key 0x621E9F35:
 Userid     : "Docker Release (CE rpm) <docker@docker.com>"
 Fingerprint: 060a 61c5 1b55 8a7f 742b 77aa c52f eb6b 621e 9f35
 From       : https://download.docker.com/linux/centos/gpg
Is this ok [y/N]:

```

Type *y* to allow the operation to complete.

Log info

```
Downloading packages:
(1/9): container-selinux-2.119.2-1.911c772.el7_8.noarch.rpm                                                                                                                             |  40 kB  00:00:00
warning: /var/cache/yum/x86_64/7/docker-ce-stable/packages/containerd.io-1.4.3-3.1.el7.x86_64.rpm: Header V4 RSA/SHA512 Signature, key ID 621e9f35: NOKEY                    ]  20 MB/s |  18 MB  00:00:04 ETA
Public key for containerd.io-1.4.3-3.1.el7.x86_64.rpm is not installed
(2/9): containerd.io-1.4.3-3.1.el7.x86_64.rpm                                                                                                                                           |  33 MB  00:00:01
(3/9): docker-ce-cli-20.10.3-3.el7.x86_64.rpm                                                                                                                                           |  33 MB  00:00:00
(4/9): docker-ce-20.10.3-3.el7.x86_64.rpm                                                                                                                                               |  27 MB  00:00:02
(5/9): fuse-overlayfs-0.7.2-6.el7_8.x86_64.rpm                                                                                                                                          |  54 kB  00:00:00
(6/9): libseccomp-2.3.1-4.el7.x86_64.rpm                                                                                                                                                |  56 kB  00:00:00
(7/9): docker-ce-rootless-extras-20.10.3-3.el7.x86_64.rpm                                                                                                                               | 9.0 MB  00:00:00
(8/9): slirp4netns-0.4.3-4.el7_8.x86_64.rpm                                                                                                                                             |  81 kB  00:00:00
(9/9): fuse3-libs-3.6.1-4.el7.x86_64.rpm                                                                                                                                                |  82 kB  00:00:00
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Total                                                                                                                                                                           39 MB/s | 102 MB  00:00:02
Retrieving key from https://download.docker.com/linux/centos/gpg
Importing GPG key 0x621E9F35:
 Userid     : "Docker Release (CE rpm) <docker@docker.com>"
 Fingerprint: 060a 61c5 1b55 8a7f 742b 77aa c52f eb6b 621e 9f35
 From       : https://download.docker.com/linux/centos/gpg
Is this ok [y/N]: y
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  Installing : libseccomp-2.3.1-4.el7.x86_64                                                                                                                                                               1/9
  Installing : 2:container-selinux-2.119.2-1.911c772.el7_8.noarch                                                                                                                                          2/9
  Installing : containerd.io-1.4.3-3.1.el7.x86_64                                                                                                                                                          3/9
  Installing : slirp4netns-0.4.3-4.el7_8.x86_64                                                                                                                                                            4/9
  Installing : 1:docker-ce-cli-20.10.3-3.el7.x86_64                                                                                                                                                        5/9
  Installing : fuse3-libs-3.6.1-4.el7.x86_64                                                                                                                                                               6/9
  Installing : fuse-overlayfs-0.7.2-6.el7_8.x86_64                                                                                                                                                         7/9
  Installing : 3:docker-ce-20.10.3-3.el7.x86_64                                                                                                                                                            8/9
  Installing : docker-ce-rootless-extras-20.10.3-3.el7.x86_64                                                                                                                                              9/9
  Verifying  : fuse3-libs-3.6.1-4.el7.x86_64                                                                                                                                                               1/9
  Verifying  : 3:docker-ce-20.10.3-3.el7.x86_64                                                                                                                                                            2/9
  Verifying  : fuse-overlayfs-0.7.2-6.el7_8.x86_64                                                                                                                                                         3/9
  Verifying  : slirp4netns-0.4.3-4.el7_8.x86_64                                                                                                                                                            4/9
  Verifying  : 2:container-selinux-2.119.2-1.911c772.el7_8.noarch                                                                                                                                          5/9
  Verifying  : libseccomp-2.3.1-4.el7.x86_64                                                                                                                                                               6/9
  Verifying  : containerd.io-1.4.3-3.1.el7.x86_64                                                                                                                                                          7/9
  Verifying  : docker-ce-rootless-extras-20.10.3-3.el7.x86_64                                                                                                                                              8/9
  Verifying  : 1:docker-ce-cli-20.10.3-3.el7.x86_64                                                                                                                                                        9/9

Installed:
  containerd.io.x86_64 0:1.4.3-3.1.el7                                  docker-ce.x86_64 3:20.10.3-3.el7                                  docker-ce-cli.x86_64 1:20.10.3-3.el7

Dependency Installed:
  container-selinux.noarch 2:2.119.2-1.911c772.el7_8 docker-ce-rootless-extras.x86_64 0:20.10.3-3.el7 fuse-overlayfs.x86_64 0:0.7.2-6.el7_8 fuse3-libs.x86_64 0:3.6.1-4.el7 libseccomp.x86_64 0:2.3.1-4.el7
  slirp4netns.x86_64 0:0.4.3-4.el7_8

Complete!

```


Step 3: Start  Docker  

Although you have installed Docker on CentOS, the service is still not running.

To start the service, enable it to run at startup. Run the following commands in the order listed below.

Start Docker:

```python


$ sudo systemctl start docker

```

Enable Docker:



```python

$ sudo systemctl enable docker

```

Log info

```
Created symlink from /etc/systemd/system/multi-user.target.wants/docker.service to /usr/lib/systemd/system/docker.service.

```

Verify that Docker Engine is installed correctly by running the hello-world image.


```python

$ sudo docker run hello-world


```

Log info


```

Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
0e03bdcc26d7: Pull complete
Digest: sha256:95ddb6c31407e84e91a986b004aee40975cb0bda14b5949f6faac5d2deadb4b9
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/
```



# Install peregrine via docker


```python

$ sudo docker pull cschin/peregrine:latest

```


Log info


```
latest: Pulling from cschin/peregrine
68ced04f60ab: Pull complete
9c388eb6d33c: Pull complete
96cf53b3a9dd: Pull complete
a6375835cc11: Pull complete
a6123f81f236: Pull complete
c192c677363e: Pull complete
72feafb40a2a: Pull complete
f87048dde396: Pull complete
b705c81cb779: Pull complete
479a525deff5: Pull complete
a50bb7798bdb: Pull complete
7a9fe8f5c810: Pull complete
b76d2d9f7e01: Pull complete
1fd67a3594ad: Pull complete
a58845b42830: Pull complete
2cbfcd7ac990: Pull complete
d7894c8c1c54: Pull complete
defb7009fa0e: Pull complete
21feb2a2fb0a: Pull complete
Digest: sha256:4f8fbc85c65d57ab0aad0fa430484aebba6271483edba2edf7f77e468aeaeed5
Status: Downloaded newer image for cschin/peregrine:latest
docker.io/cschin/peregrine:latest

```


prepare the input file

find /home/kplee/datafile/001.i.bat.pacbio.hifi.reads/ -name "S_unknown.ccs.merged.fasta" | sort > seqdata.lst 

docker run -it -v //home/kplee/analysis/01.peregrine_assembly_sweetpotato_pacbio_hifi_data://home/kplee/analysis/01.peregrine_assembly_sweetpotato_pacbio_hifi_data \ cschin/peregrine:latest asm \
/home/kplee/analysis/01.peregrine_assembly_sweetpotato_pacbio_hifi_data/seqdata.lst \ 
--with-consensus --shimmer-r 3 --best_n_ovlp 8 \ 



/usr/bin/time -o out.txt -v sudo docker run -it -v /home/kplee/analysis/01.peregrine_assembly_sweetpotato_pacbio_hifi_data:/wd \
--user $(id -u):$(id -g) cschin/peregrine:latest asm \
/home/kplee/analysis/01.peregrine_assembly_sweetpotato_pacbio_hifi_data/seqdata.lst 32 32 32 32 32 32 32 32 32 --with-consensus --with-alt --shimmer-r 3 \
--best n ovlp 8 --output /home/kplee/analysis/01.peregrine_assembly_sweetpotato_pacbio_hifi_data/









Install ggc compiler version 9.3 using conda

```python

$ conda install -c conda-forge gcc_linux-64

```



Log info

```
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /home/kplee/program/miniconda3

  added / updated specs:
    - gcc_linux-64


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    binutils_impl_linux-64-2.35.1|       hd53bc6c_1         9.5 MB
    binutils_linux-64-2.35     |      hc3fd857_29          22 KB  conda-forge
    ca-certificates-2020.12.5  |       ha878542_0         137 KB  conda-forge
    certifi-2020.12.5          |   py38h578d9bd_1         143 KB  conda-forge
    conda-4.9.2                |   py38h578d9bd_0         3.0 MB  conda-forge
    gcc_impl_linux-64-9.3.0    |      h70c0ae5_18        43.1 MB  conda-forge
    gcc_linux-64-9.3.0         |      h7247604_29          23 KB  conda-forge
    kernel-headers_linux-64-2.6.32|      h77966d4_13         707 KB  conda-forge
    libgcc-devel_linux-64-9.3.0|      h7864c58_18         4.0 MB  conda-forge
    openssl-1.1.1i             |       h7f98852_0         2.1 MB  conda-forge
    python_abi-3.8             |           1_cp38           4 KB  conda-forge
    sysroot_linux-64-2.12      |      h77966d4_13        30.2 MB  conda-forge
    ------------------------------------------------------------
                                           Total:        93.0 MB

The following NEW packages will be INSTALLED:

  binutils_impl_lin~ pkgs/main/linux-64::binutils_impl_linux-64-2.35.1-hd53bc6c_1
  binutils_linux-64  conda-forge/linux-64::binutils_linux-64-2.35-hc3fd857_29
  gcc_impl_linux-64  conda-forge/linux-64::gcc_impl_linux-64-9.3.0-h70c0ae5_18
  gcc_linux-64       conda-forge/linux-64::gcc_linux-64-9.3.0-h7247604_29
  kernel-headers_li~ conda-forge/noarch::kernel-headers_linux-64-2.6.32-h77966d4_13
  libgcc-devel_linu~ conda-forge/linux-64::libgcc-devel_linux-64-9.3.0-h7864c58_18
  python_abi         conda-forge/linux-64::python_abi-3.8-1_cp38
  sysroot_linux-64   conda-forge/noarch::sysroot_linux-64-2.12-h77966d4_13

The following packages will be UPDATED:

  certifi            pkgs/main::certifi-2020.12.5-py38h06a~ --> conda-forge::certifi-2020.12.5-py38h578d9bd_1

The following packages will be SUPERSEDED by a higher-priority channel:

  ca-certificates    pkgs/main::ca-certificates-2021.1.19-~ --> conda-forge::ca-certificates-2020.12.5-ha878542_0
  conda               pkgs/main::conda-4.9.2-py38h06a4308_0 --> conda-forge::conda-4.9.2-py38h578d9bd_0
  openssl              pkgs/main::openssl-1.1.1i-h27cfd23_0 --> conda-forge::openssl-1.1.1i-h7f98852_0


Proceed ([y]/n)?


```
Press *y*





Log info


```
Downloading and Extracting Packages
ca-certificates-2020 | 137 KB    | #################################################################################################################################################################### | 100%
binutils_linux-64-2. | 22 KB     | #################################################################################################################################################################### | 100%
python_abi-3.8       | 4 KB      | #################################################################################################################################################################### | 100%
certifi-2020.12.5    | 143 KB    | #################################################################################################################################################################### | 100%
binutils_impl_linux- | 9.5 MB    | #################################################################################################################################################################### | 100%
gcc_impl_linux-64-9. | 43.1 MB   | #################################################################################################################################################################### | 100%
openssl-1.1.1i       | 2.1 MB    | #################################################################################################################################################################### | 100%
libgcc-devel_linux-6 | 4.0 MB    | #################################################################################################################################################################### | 100%
conda-4.9.2          | 3.0 MB    | #################################################################################################################################################################### | 100%
kernel-headers_linux | 707 KB    | #################################################################################################################################################################### | 100%
gcc_linux-64-9.3.0   | 23 KB     | #################################################################################################################################################################### | 100%
sysroot_linux-64-2.1 | 30.2 MB   | #################################################################################################################################################################### | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: done


```



### Today 31 March 2021

On new Centos

First install gcc


```

sudo yum group install "Development Tools"

```


Check 

```

gcc --version
```



Got this


```

[yedomon@localhost]$ gcc --version
gcc (GCC) 4.8.5 20150623 (Red Hat 4.8.5-44)
Copyright (C) 2015 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

```


Now trying to install PAML tool

```
$ wget http://abacus.gene.ucl.ac.uk/software/paml4.9j.tgz
$ tar xf paml4.9j.tgz
$ cd paml4.9j
$ rm bin/*.exe
$ cd src
$ make -f Makefile
$ ls -lF
$ mv baseml basemlg codeml pamp evolver yn00 mcmctree chi2 ../bin
```

## gbextractor installation


```

sudo yum install python3-pip.noarch

sudo pip3 install gbseqextractor

 gbseqextractor --help

```

info


```

usage: gbseqextractor [-h] -f <STR> -prefix <STR> [-seqPrefix <STR>]
                      [-types {CDS,rRNA,tRNA,wholeseq,gene} [{CDS,rRNA,tRNA,wholeseq,gene} ...]]
                      [-cds_translation] [-gi] [-p] [-t] [-s] [-l] [-rv] [-F]

Extract any CDS or rNRA or tRNA DNA sequences of genes from Genbank file.

Seqid will be the value of '/gene=' or '/product=', if they both were not
present, the gene will not be output!

version 20201128:
    Now we can handle compounlocation (feature location with "join")!
    We can also output the translation for each CDS (retrived from '/translation=')

Please cite:
Guanliang Meng, Yiyuan Li, Chentao Yang, Shanlin Liu,
MitoZ: a toolkit for animal mitochondrial genome assembly, annotation
and visualization, Nucleic Acids Research, https://doi.org/10.1093/nar/gkz173



optional arguments:
  -h, --help            show this help message and exit
  -f <STR>              Genbank file
  -prefix <STR>         prefix of output file. required.
  -seqPrefix <STR>      prefix of each seq id. default: None
  -types {CDS,rRNA,tRNA,wholeseq,gene} [{CDS,rRNA,tRNA,wholeseq,gene} ...]
                        what kind of genes you want to extract? wholeseq for
                        whole fasta seq. WARNING: Each sequence in the result
                        files corresponds to ONE feature in the GenBank file,
                        I will NOT combine multiple CDS of the same gene into
                        ONE! [CDS]
  -cds_translation      Also output translated CDS (required -types CDS). The
                        translations are retrived directly from the
                        '/translation=' key word. [False]
  -gi                   use gi number as sequence ID instead of accession
                        number when " gi number is present. (default:
                        accession number)
  -p                    output the position information on the ID line.
                        Warning: the position on ID line is 0 left-most!
                        [False]
  -t                    output the taxonomy lineage on ID line [False]
  -s                    output the species name on the ID line [False]
  -l                    output the seq length on the ID line [False]
  -rv                   reverse and complement the sequences if the gene is on
                        minus strand. Always True!
  -F                    only output full length genes,i.e., exclude the genes
                        with '>' or '<' in their location [False]

```
