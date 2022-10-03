# My_Tar-Qwasar
# Welcome to My Tar
***
![image](https://user-images.githubusercontent.com/96412090/193509705-0b71d6da-15c3-4245-8eed-ab631a42c647.png)


## Task

TODO - My Tar

## Description

my_tar is a command to manipulate tape archive. The first option to tar is a mode indicator from the following list.
- -c Create a new archive containing the specified items.
- -r Like -c, but new entries are appended to the archive. The -f option is required.
- -t List archive contents to stdout.
- -u Like -r, but new entries are added only if they have a modification date newer than the corresponding entry in the archive. The -f option is required.
- -x Extract to disk from the archive. If a file with the same name appears more than once in the archive, each copy will be extracted, with later copies overwriting (replacing) earlier copies.




## Installation

make

## Usage

```
    make
    ./my_tar -cf file.tar source.c source.h
    ./my_tar -tf file.tar
    ./my_tar -xf file.tar return the file
    ./my_tar -uf file.tar file

```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar Silicon Valley</a></i></span>
<span><img alt='Qwasar Silicon Valley Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
