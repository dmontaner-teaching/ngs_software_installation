GATK
====

Download the program form <https://www.broadinstitute.org/gatk/> (signin agreement is required)

Once you have uncompressed the file you can execute the __java__ file doing:

    java -jar GenomeAnalysisTK.jar


You may create an "executable" doing this:

Create a file called __GATK__ containing this lines:

    #!/bin/bash
    java -jar ~/bin/NGS/GenomeAnalysisTK-3.2-2/GenomeAnalysisTK.jar $@

and leave the file in your `bin` directory or add it to your path.

Then you can call gatk just by typing:

   GATK parameters

