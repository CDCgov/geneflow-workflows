# GeneFlow Public Reference Workflows

This repository contains a catalog of public reference workflows for GeneFlow, a workflow engine for bioinformatics and public health analytics. 

GeneFlow is open source: 

* [Version 1.x](https://github.com/CDCgov/geneflow)

* [Version 2.x](https://github.com/CDCgov/geneflow2)


## Public Reference Workflows

Public reference workflows and apps can be found here: https://gitlab.com/geneflow. Information for each workflow can be found below: 

* [BWA Sequence Alignment](https://gitlab.com/geneflow/workflows/bwa-gf.git)
    * This workflow aligns paired-end sequences to a reference using BWA. 
    * GeneFlow Version: 1.x
    * GeneFlow Apps:
        * [BWA Index](https://gitlab.com/geneflow/apps/bwa-index-gf.git)
        * [BWA Mem](https://gitlab.com/geneflow/apps/bwa-mem-gf.git)

* [BWA Sequence Alignment (v2)](https://gitlab.com/geneflow/workflows/bwa-gf2.git)
    * This workflow aligns paired-end sequences to a reference using BWA. 
    * GeneFlow Version: 2.x
    * GeneFlow Apps:
        * [BWA Index](https://gitlab.com/geneflow/apps/bwa-index-gf2.git)
        * [BWA Mem](https://gitlab.com/geneflow/apps/bwa-mem-gf2.git)

* [GATK Variant Calling](https://gitlab.com/geneflow/workflows/gatk-variants-gf2.git)
    * Trim, align, and call variants with GATK Haplotypecaller.
    * GeneFlow Version: 2.x
    * GeneFlow Apps:
        * [Mask Repeats](https://gitlab.com/geneflow/apps/mask-repeats-gf2.git)
        * [BWA Index](https://gitlab.com/geneflow/apps/bwa-index-gf2.git)
        * [Index Reference](https://gitlab.com/geneflow/apps/index-reference-gf2.git)
        * [FaQCs](https://git.biotech.cdc.gov/geneflow-apps/faqcs-gf2.git) 
        * [BWA Align](https://gitlab.com/geneflow/apps/bwa-align-gf2.git)
        * [BAM Sort](https://git.biotech.cdc.gov/geneflow-apps/bam-sort-gf2.git)
        * [Picard Mark Duplicates](https://git.biotech.cdc.gov/geneflow-apps/picard-markduplicates-gf2.git)
        * [Picard Clean SAM](https://git.biotech.cdc.gov/geneflow-apps/picard-cleansam-gf2.git)
        * [Picard Fix Mate Information](https://git.biotech.cdc.gov/geneflow-apps/picard-fixmateinformation-gf2.git)
        * [Picard Add or Replace Read Groups](https://git.biotech.cdc.gov/geneflow-apps/picard-addorreplacereadgroups-gf2.git)
        * [BAM Index](https://git.biotech.cdc.gov/geneflow-apps/bam-index-gf2.git)
        * [GATK Haplotype Caller](https://gitlab.com/geneflow/apps/gatk-haplotypecaller-gf2.git)
        * [GATK Combine gVCFs](https://gitlab.com/geneflow/apps/gatk-combinegvcfs-gf2.git)
        * [GATK Genotype gVCFs](https://gitlab.com/geneflow/apps/gatk-genotypegvcfs-gf2.git)
        * [GATK Variant Filtration](https://gitlab.com/geneflow/apps/gatk-variantfiltration-gf2.git)
        * [GATK Select Variants](https://gitlab.com/geneflow/apps/gatk-selectvariants-gf2.git)

* [Nanopore Amplicon Dereplication](https://gitlab.com/geneflow/workflows/nanopore-amplicon-dereplication-gf.git)
    * This workflow takes basecalled, demultiplexed, and trimmed FASTQ files from Nanopore sequencing. It uses Canu to dereplicate the reads into amplicons, then uses Medaka to polish the amplicons using the trimmed FASTQ files. 
    * GeneFlow Version: 1.x
    * GeneFlow Apps:
        * [Canu](https://gitlab.com/geneflow/apps/canu-gf.git)
        * [Medaka](https://gitlab.com/geneflow/apps/medaka-gf.git)

* [NCBI SRA Uploader](https://gitlab.com/geneflow/workflows/ncbi-sra-uploader-gf2.git)
    * This workflow is an FTP bulk upload tool for NCBI SRA data. 
    * GeneFlow Version: 2.x
    * GeneFlow Apps:
        * [NCBI SRA FTP Uploader](https://gitlab.com/geneflow/apps/ncbi-lftp-sra-gridengine-upload-tool-gf2.git)

* [NCBI GEO Uploader](https://gitlab.com/geneflow/workflows/ncbi-lftp-geo-upload-tool-workflow.git)
    * This workflow is an FTP build upload tool for NCBI GEO data. 
    * GeneFlow Version: 1.x
    * GeneFlow Apps:
        * [NCBI GEO FTP Uploader](https://gitlab.com/geneflow/apps/ncbi-lftp-geo-upload-tool-gf.git)

* [SanitizeMe](https://gitlab.com/geneflow/workflows/sanitize-me-gf.git)
    * This workflow removes host sequences from reads using Minimap2 and SAMTools.
    * GeneFlow Version: 1.x
    * GeneFlow Apps:
        * [Minimap2](https://gitlab.com/geneflow/apps/minimap2-gf.git)
        * [SAMTools Filter Flags](https://gitlab.com/geneflow/apps/samtools-filter-flags-gf.git)
        * [SAMTools BAM to FASTQ](https://gitlab.com/geneflow/apps/samtools-bam-to-fastq-gf.git)

* [SanitizeMe Paired](https://gitlab.com/geneflow/workflows/sanitize-me-paired-gf.git)
    * This workflow removes host sequences from paired-end reads using Minimap2 and SAMTools.
    * GeneFlow Version: 1.x
    * GeneFlow Apps:
        * [SanitizeMe Paired Container](https://gitlab.com/geneflow/apps/sanitizemepaired-gf.git)
 

## Development Team and Support

GeneFlow and the public reference workflows were developed by the GDIT Scientific Computing and Bioinformatics Support (SCBS) team for the Office of Advanced Molecular Detection (OAMD) at the CDC.

For technical support, please contact oamdsupport@cdc.gov.
  
## Public Domain

This repository constitutes a work of the United States Government and is not
subject to domestic copyright protection under 17 USC § 105. This repository is in
the public domain within the United States, and copyright and related rights in
the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
All contributions to this repository will be released under the CC0 dedication. By
submitting a pull request you are agreeing to comply with this waiver of
copyright interest.

## License

The repository utilizes code licensed under the terms of the Apache Software
License and therefore is licensed under ASL v2 or later.

This source code in this repository is free: you can redistribute it and/or modify it under
the terms of the Apache Software License version 2, or (at your option) any
later version.

This source code in this repository is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the Apache Software License for more details.

You should have received a copy of the Apache Software License along with this
program. If not, see http://www.apache.org/licenses/LICENSE-2.0.html

The source code forked from other open source projects will inherit its license.

## Privacy

This repository contains only non-sensitive, publicly available data and
information. All material and community participation is covered by the
Surveillance Platform [Disclaimer](https://github.com/CDCgov/template/blob/master/DISCLAIMER.md)
and [Code of Conduct](https://github.com/CDCgov/template/blob/master/code-of-conduct.md).
For more information about CDC's privacy policy, please visit [http://www.cdc.gov/privacy.html](http://www.cdc.gov/privacy.html).

## Contributing

Anyone is encouraged to contribute to the repository by [forking](https://help.github.com/articles/fork-a-repo)
and submitting a pull request. (If you are new to GitHub, you might start with a
[basic tutorial](https://help.github.com/articles/set-up-git).) By contributing
to this project, you grant a world-wide, royalty-free, perpetual, irrevocable,
non-exclusive, transferable license to all users under the terms of the
[Apache Software License v2](http://www.apache.org/licenses/LICENSE-2.0.html) or
later.

All comments, messages, pull requests, and other submissions received through
CDC including this GitHub page are subject to the [Presidential Records Act](http://www.archives.gov/about/laws/presidential-records.html)
and may be archived. Learn more at [http://www.cdc.gov/other/privacy.html](http://www.cdc.gov/other/privacy.html).

## Records

This repository is not a source of government records, but is a copy to increase
collaboration and collaborative potential. All government records will be
published through the [CDC web site](http://www.cdc.gov).

## Notices

Please refer to [CDC's Template Repository](https://github.com/CDCgov/template)
for more information about [contributing to this repository](https://github.com/CDCgov/template/blob/master/CONTRIBUTING.md),
[public domain notices and disclaimers](https://github.com/CDCgov/template/blob/master/DISCLAIMER.md),
and [code of conduct](https://github.com/CDCgov/template/blob/master/code-of-conduct.md).

