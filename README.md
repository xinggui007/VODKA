# VODKA
## Viral Open-source DVG Key Algorithm

### Usage

    VODKA --genomeFA <input fasta> --queryInput <file of fastq/fasta> --outDir <output directory> \
    --bt2Dir <bowtie2 directory> [options]

* --genomeFA &lt;input fasta> : viral genome fasta file.
* --queryInput &lt;fastq/fastq> : a file with full path of fastq or fasta files for alignment. fastq/fasta files can be gzip'ed.
* --outDir &lt;output directory> : full path to output directory.
* --bt2Dir &lt;bowtie2 directory> : full path to bowtie2-2.2.9 directory. (where bowtie2 and bowtie2-build is located)

* options : <br>
    * -bp_from_right &lt;n> : &lt;n> is number of bases from right. (default: 3000)
    * -h/--help : print this usage.

### Requirements
* bowtie2-2.2.9: <br>
Download bowtie2-2.2.9 from [here.](https://sourceforge.net/projects/bowtie-bio/files/bowtie2/2.2.9)
* RAM: <br>
2G per fastq/fasta file. 

