## Downloading data from SRA directly to MSI

I'm not sure if there's a good way to get a list of the SRA IDs without doing lots of clicking... this is what I did.

`````
wget https://sra-pub-run-odp.s3.amazonaws.com/sra/SRR11818966/SRR11818966

##This downloads an SRA file that needs to be unpacked with SRA tools

module load sratoolkit

fastq-dump SRR11818966
`````

This should output a pair of fastq files (read1 and read2) \
ugh.  This just gives a single fastq file.  I am trying to add the "--split-3" command which should give "read1", "read2", "orphan reads".. let us hope
