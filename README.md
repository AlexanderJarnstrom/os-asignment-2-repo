# OS Asignment 2

In this assignment several page replacement algorithems will be tested, with two different files containing long lists of memory refrences, to see which is more suited for the job.

* First in, First out (FIFO)
* Least Recently Used (LRU)
* Optimal

## Usage

### Install

cd to directory

    $ cd [saved directory]

Install

    $ ./install.sh

if premison errors run

    $ chmod 755 install.sh

, then install.

### Compile

cd to directory

    $ cd [saved directory]

Compile the makefile

    $ make

cd to output directory

    $ cd out/

### First in, First out (FIFO)

    $ ./fifo [page_count] [page_size] [file_path]

### Least Recently Used (LRU)

    $ ./lru [page_count] [page_size] [file_path]

### Optimal

    $ ./optimal [page_count] [page_size] [file_path]

### Output

    Total [refrence count] | Page size: [page size] | Pages: [page count]
    Page faults: [number of page faults]
