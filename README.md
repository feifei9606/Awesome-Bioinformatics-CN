# Awesome Bioinformatics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Check URLs](https://github.com/feifei9606/Awesome-Bioinformatics-CN/actions/workflows/url-check.yml/badge.svg)](https://github.com/feifei9606/Awesome-Bioinformatics-CN/actions/workflows/url-check.yml) [![Lint Code Base](https://github.com/feifei9606/Awesome-Bioinformatics-CN/actions/workflows/linter.yml/badge.svg)](https://github.com/feifei9606/Awesome-Bioinformatics-CN/actions/workflows/linter.yml)

> 生物信息学（英语：bioinformatics）利用应用数学、信息学、统计学和计算机科学的方法研究生物学的问题。--[维基百科](https://zh.wikipedia.org/wiki/%E7%94%9F%E7%89%A9%E4%BF%A1%E6%81%AF%E5%AD%A6)

本仓库`fork`自[https://github.com/danielecook/Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics)，为其汉化版，同时加上一些笔者在科研/工作中比较好用的生物信息学工具/数据库等。共同学习，共同进步。Help you，Help us。

---

生物信息学软件，资源和工具库的精选列表。 大多数为命令行，免费或开源工具。 欢迎提交[pull request](./CONTRIBUTING.md)~

---

## 软件包套件

软件包套件收录用于特定语言或平台的生物信息学软件包和安装工具。 

- **[Bioconductor](https://github.com/Bioconductor)** - 基于`R`语言的用于分析高通量数据的工具平台，截至到3.12版本已收录1900多个软件包[ [paper-2004](https://link.springer.com/article/10.1186/gb-2004-5-10-r80) | [web](https://www.bioconductor.org) ]
- **[Biopython](https://github.com/biopython/biopython)** - 基于`Python`的进行生物计算的免费工具，包括使用技巧，包以及详细文档。属于 [Open Bioinformatics Foundation](http://open-bio.org/)的一部分，同时也包含NCBI eutils的API来访问NCBI数据库[ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19304878) | [web](https://biopython.org) ]
- **[Bioconda](https://github.com/bioconda)** - [conda包管理器](http://conda.pydata.org/docs/intro.html)中专门针对生物信息学软件的一个channel，包括3000+的生物信息学软件包[ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29967506) | [web](https://bioconda.github.io) ]
- **[BioJulia](https://github.com/BioJulia)** - 基于`Jujia`的生物信息学和计算生物学框架[ [web](https://biojulia.net) ]
- **[Rust-Bio](https://github.com/rust-bio/rust-bio)** - 基于`Rust`的生物信息学常见数据结构和算法[ [paper-2016](http://bioinformatics.oxfordjournals.org/content/early/2015/10/06/bioinformatics.btv573.short?rss=1) ]
- **[SeqAn](https://github.com/seqan/seqan3)** - 基于`C++`的序列分析库
- **[(Poly)merase](https://github.com/TimothyStiles/poly)** - 合成生物学GO库和命令行工具
- **[Biocaml](https://github.com/biocaml/biocaml)** - 基于OCaml的高性能生物信息库
- **[Biojava](https://github.com/biojava/biojava)** - 处理生物数据的Java框架

## 数据下载

- **[GGD](https://github.com/gogetdata/ggd-cli)** - Go Get Data; 命令行下载基因组数据 [ [web](https://gogetdata.github.io) ]
- **[SRA-Explorer](https://github.com/ewels/sra-explorer)** - 快速获得SRA下载链接和其它信息 [ [web](https://sra-explorer.info) ]

## 数据压缩

- **[Genozip](https://github.com/divonlan/genozip)** :thumbsup: - 常见基因组文件格式(BAM, CRAM, FASTQ, VCF等)压缩 [ [web](https://genozip.readthedocs.io/) | [paper-2021](http://dx.doi.org/10.1093/bioinformatics/btab102) ]
- **[gtz](https://github.com/Genetalks/gtz)** :thumbsup:,  人和未来开发的高性能高压缩效率的工具

## 数据处理

### 命令行工具

- **[Bioinformatics One Liners](https://github.com/stephenturner/oneliners)** - 只一行命令进行生物数据处理
- **[BioNode](https://github.com/bionode/bionode)** - 模块化和通用的生物信息学工具，Bionode为生物信息学分析工作流提供了可移植的UNIX命令行工具和JavaScript API [ [web](http://bionode.io) ]
- **[bioSyntax](https://github.com/bioSyntax/bioSyntax)** - vim/less/gedit/submie中生物数据格式(SAM, VCF, GTF, FASTA, PDB等)语法高亮 [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30134911) | [web](http://www.bioSyntax.org) ]
- **[CSVKit](https://github.com/wireservice/csvkit)** - 操作CSV/TAB分割文件的工具 [ [web](https://csvkit.readthedocs.io/en/latest) ]
- **[csvtk](https://github.com/shenwei356/csvtk)** - 另一个跨平台，高效实用的CSV/TSV工具箱 [ [web](https://bioinf.shenwei.me/csvtk) ]
- **[datamash](https://git.savannah.gnu.org/gitweb/?p=datamash.git)** - 数据转换和统计 [ [web](http://www.gnu.org/software/datamash) ]
- **[easy_qsub](https://github.com/shenwei356/easy_qsub)** - 使用脚本模板快速提交PBS任务，支持多个输入文件
- **GNU Parallel** - 在一台多核的机器上并行执行任务的通用并行器，[这里](https://www.biostars.org/p/63816/)是使用GNU cParallel的一些示例。
- **[grabix](https://github.com/arq5x/grabix)** - 随机访问BGZF文件的轻量工具。
- **[grepq](https://github.com/Rbfinch/grepq)** - 通过一条或多条正则表达式匹配reads，实现FASTQ快速过滤
- **[gsort](https://github.com/brentp/gsort)** - 按照指定顺序排序基因文件
- **[tabix](https://github.com/samtools/tabix)** - 表格数据建立索引 [ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21208982) ]
- **[wormtable](https://github.com/wormtable/wormtable)** - 大型数据集单写多读
- **[zindex](https://github.com/mattgodbolt/zindex)** - 压缩文本文件创建索引
- **[jq](https://github.com/stedolan/jq)​**:thumbsup: - 命令行处理JSON文件
- screen :thumbsup: - 命令行终端切换软件
- **[tmux](https://github.com/tmux/tmux)**:thumbsup: - 终端多路复用器，可以在一个屏幕上创建，访问，控制多个终端。同时可以断开连接并继续在后台运行

## 二代测序

### 流程管理

- **[BigDataScript](https://github.com/pcingola/BigDataScript)** - 跨系统脚本语言，用于处理具有不同算力的计算机系统中的大数据流程的跨系统脚本语言 [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25189778) | [web](https://pcingola.github.io/BigDataScript) ]
- **[Bpipe](https://github.com/ssadedin/bpipe)** - 一种定义流程不同阶段及串联起来的轻量语言 [ [web](http://docs.bpipe.org) ]
- **[Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language)** - 用于描述分析工作流程和工具的规范，从工作站到集群，云和高性能计算（HPC）环境的各种软件和硬件环境中都具有可移植性和可伸缩性 [ [web](http://www.commonwl.org) ]
- **[Cromwell](https://github.com/broadinstitute/cromwell)** - 面向科学工作流程的工作流程管理系统 [ [web](https://cromwell.readthedocs.io) ]
- **[Galaxy](https://github.com/galaxyproject)** - 一个流行的开源，基于Web的平台，用于数据密集型生物医学研究。 从数据分析到工作流管理再到可视化工具一站式解决 [ [paper-2018](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6030816) | [web](https://galaxyproject.org) ]
- **[Nextflow](https://github.com/nextflow-io/nextflow) :thumbsup:** - 基于UNIX管道概念建模的流畅DSL，简化了以可移植方式编写并行和可扩展管道的过程。 [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29412134) | [web](http://nextflow.io) ]
- **[redun](https://github.com/insitro/redun)** - 基于Python的流程管理工具
- **[Ruffus](https://github.com/cgat-developers/ruffus)** - 广泛用于科学和生物信息的计算流程Python库[ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/20847218) | [web](http://www.ruffus.org.uk) ]
- **[SciPipe](https://github.com/scipipe/scipipe)** - 嵌入Go语言的流程库，专注于支持复杂流程结构、编译为单个可执行文件，并为每个输出提供强大的文件命名和完善的审计报告 [ [paper-2019](https://pubmed.ncbi.nlm.nih.gov/31029061/) | [web](https://scipipe.org/) ]
- **[SeqWare](https://github.com/SeqWare/seqware)** - 基于Hadoop Oozie的工作流系统用于云环境中的基因组数据分析 [ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/21210981) | [web](https://seqware.github.io) ]
- **[Snakemake](https://github.com/snakemake/snakemake)**:thumbsup: - Python中的工作流管理系统，旨在通过提供快速舒适的执行环境来降低创建工作流的复杂性 [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29788404) | [web](https://snakemake.readthedocs.io) ]
- **[Workflow Descriptor Language](https://github.com/broadinstitute/wdl)** - Broad开发的流程标准(已archived) [ [web](https://software.broadinstitute.org/wdl) ]

### 生信流程

- **[Awesome-Pipeline](https://github.com/pditommaso/awesome-pipeline)** - 流程资源列表
- **[Bactopia](https://github.com/bactopia/bactopia/)** - 基于Nextflow的细菌基因组分析流程 [ [web](https://bactopia.github.io/) ]
- **[bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen)** - 已验证可扩展的，社区开发的变异检测，注释，预测，RNA-seq和小RNA分析流程 [ [web](https://bcbio-nextgen.readthedocs.io) ]
- **[snakepipes](https://github.com/maxplanck-ie/snakepipes):thumbsup:** - 基于snakemake的流程，包括ChIP-seq，mRNA-seq， noncoding-RNA-seq， ATAC-seq， scRNA-seq，Hi-C，Whole Genome Bisulfite Seq/WGBS [ [paper-2019](https://academic.oup.com/bioinformatics/article/35/22/4757/5499080) ]
- **[nf-core](https://github.com/nf-core)**:thumbsup: - 基于Nextflow的社群维护的精选分析流程
- **[ngs-preprocess](https://github.com/fmalmeida/ngs-preprocess)** - 基于Nextflow的预处理短/长读长reads流程 [ [web](https://ngs-preprocess.readthedocs.io/en/latest/?badge=latest) ]

### 格式转化

- **[seqmagick](https://github.com/fhcrc/seqmagick)** - 方便使用Biopython进行文件格式转化 [ [web](http://seqmagick.readthedocs.io) ]
- **[bioconvert](https://github.com/bioconvert/bioconvert)** :thumbsup: - 目前支持45种格式，95种转换[ [web](https://bioconvert.readthedocs.io/en/master/) ] 

### 序列处理

序列处理包括对原始测序数据拆分（demultiplexing）、去除接头和低质量序列。

- **[AfterQC](https://github.com/OpenGene/AfterQC)** - 对FASTQ数据自动过滤，triming，移除错误和质控[ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28361673) ]，后作者使用C++重新实现，成为
- **[fastp](https://github.com/OpenGene/fastp)** :thumbsup: AfterQC作者使用C++重新实现 [ [paper 2018](https://academic.oup.com/bioinformatics/article/34/17/i884/5093234 )]
- **[FastQC](https://github.com/s-andrews/FastQC)** - 高通量测序数据FASTQ质控工具 [ [web](http://www.bioinformatics.babraham.ac.uk/projects/fastqc) ]
- **[Fastqp](https://github.com/mdshw5/fastqp)** - 基于`python`的FASTQ和SAM质控工具
- **[Fastx Tookit](https://github.com/agordon/fastx_toolkit)** - FASTQ/FASTA 短序列处理工具：去接头，trimming，碱基质量过滤，masking[ [web](http://hannonlab.cshl.edu/fastx_toolkit) ]
- **[fqtk](https://github.com/fulcrumgenomics/fqtk)** - 基于`Rust`的多线程FASTQ工具包，核心是`fqtk demux`按reads固定位置的barcode做样本拆分，支持双index、UMI（`M`）与单细胞barcode（`C`），另提供`shard`分片与`subsample`抽样子命令
- **[MultiQC](https://github.com/ewels/MultiQC)** :thumbsup: - 汇总多个样本的生物信息分析结果到一张报告 [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27312411) | [web](http://multiqc.info) ]
- **[SeqFu](https://github.com/telatin/seqfu2)** - 基于Nim的处理FASTA/FASTQ工具集[ [paper-2021](https://www.mdpi.com/2306-5354/8/5/59) | [web](https://telatin.github.io/seqfu2/) ]
- **[SeqKit](https://github.com/shenwei356/seqkit)** - 基于`Go`的跨平台，超快处理FASTQ/FASTQ文件的工具包[ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27706213) | [web](https://bioinf.shenwei.me/seqkit) ]
- **[Seqtk](https://github.com/lh3/seqtk)** :thumbsup:- 处理FASTA/FASTQ格式中序列的工具箱
- **[smof](https://github.com/incertae-sedis/smof)** - UNIX-风格的FASTA操作工具

### 数据分析

以下条目通过引入专门数据库支持可扩展的基因组分析

- **[Hail](https://github.com/hail-is/hail)** - 可扩展基因组分析(类似pandas？)
- **[GLNexus](https://github.com/dnanexus-rnd/GLnexus)** - 群体测序项目中可扩展gVCF合并以及联合变异检测[ [paper-2018](https://www.biorxiv.org/content/10.1101/343970v1.abstract) ]

### 序列比对

#### 双序列比对

- **[Bowtie 2](https://github.com/BenLangmead/bowtie2)** - 一种超快速且节约内存的工具，将测序序列与参考序列进行比对。[ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/22388286) | [web](http://bowtie-bio.sourceforge.net/bowtie2) ]
- **[BWA](https://github.com/lh3/bwa)** - DNA序列间两两比对的Burrow-Wheeler Aligner
- **[BWA-FastAlign](https://github.com/zzhofict/BWA-FastAlign)** - BWA-MEM的替代品：速度快2-3倍，成本低2-5倍，在标准CPU上输出结果100%一致 [ [paper-2026](https://dl.acm.org/doi/10.1145/3774934.3786421) ]
- **[minibwa](https://github.com/lh3/minibwa)** - bwa-mem的继任者，用于短读长比对。用BWT建索引+变长种子（同bwa-mem），chaining与SIMD核苷酸比对复用minimap2算法；精度相当的前提下速度是bwa-mem的3倍以上、bwa-mem2的2倍
- **[strobealign](https://github.com/ksahlin/strobealign)** - 使用strobemer动态种子长度的短读长比对工具，最佳适用读长100–500 bp，通常比同类比对器更快且准确度相当或更优，人基因组建索引4核不到1分钟 [ [paper-2022](https://doi.org/10.1186/s13059-022-02831-7) | [paper-2026](https://doi.org/10.1186/s13059-026-04017-x) ]
- **[WFA](https://github.com/smarco/WFA)** - wavefront比对算法(WFA)利用序列的相似性加速比对 [ [paper-2020](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btaa777/5904262) ]
- **[Parasail](https://github.com/jeffdaily/parasail)** - 用于全局，半全局和局部序列比对的SIMD C库[ [paper-2016](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0930-z) ]
- **[MUMmer](https://github.com/mummer4/mummer)** -  整基因组比对 [ [paper-1999](http://mummer.sourceforge.net/MUMmer.pdf) | [paper-2002](http://mummer.sourceforge.net/MUMmer2.pdf) | [paper-2004](http://mummer.sourceforge.net/MUMmer3.pdf) | [web](http://mummer.sourceforge.net) ]
- **[DIAMOND](https://github.com/bbuchfink/diamond)** - 超快速蛋白质比对工具，用于类似`blastp`和`blastx`的搜索 [ [paper-2021](https://www.nature.com/articles/s41592-021-01101-x) ]

#### 多序列比对

- **[POA](https://github.com/ljdursi/poapy)** - 偏序比对用于多序列比对以及同源序列保守序列[ [paper-2002](https://academic.oup.com/bioinformatics/article/18/3/452/236691) ]

#### 聚类

- **[MMseqs2](https://github.com/soedinglab/MMseqs2)** - 用于蛋白质和核酸序列数据集超快、敏感搜索和聚类工具 [ [paper-2017](https://www.nature.com/articles/nbt.3988) | [paper-2018](https://www.nature.com/articles/s41467-018-04964-5) ]

### 表达定量

- **[Cufflinks](https://github.com/cole-trapnell-lab/cufflinks)** - Cufflinks组装转录本，估计表达风度，RNA-seq样本差异表达和调控分析 [ [paper-2010](https://www.nature.com/articles/nbt.1621) ]
- **[RSEM](https://github.com/deweylab/RSEM)**:thumbsup: - RNA-Seq数据基因层次和转录本层次表达定量 [ [paper-2011](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-323) | [web](http://deweylab.github.io/RSEM/) ]

### 富集分析

- **[GSEApy](https://github.com/zqfang/GSEApy)**:thumbsup: - 使用Python进行基因集分析分析
- **[clusterProfiler](https://github.com/YuLab-SMU/clusterProfiler)**:thumbsup:- Y叔富集分析R包 ​

### 变异检测

- **[freebayes](https://github.com/ekg/freebayes)** - 基于贝叶斯单倍型多态性发现及基因分型 [ [web](http://arxiv.org/abs/1207.3907) ]
- **[GATK](https://github.com/broadgsa/gatk)** :thumbsup:- 高通量数据变异检测金标准[ [web](https://software.broadinstitute.org/gatk) ]
- **[deepvariant](https://github.com/google/deepvariant)**:thumbsup: - 深度学习变异检测 [ [Nature Biotechnology-2018](https://doi.org/10.1038/nbt.4235) ]
- **[Octopus](https://github.com/luntergroup/octopus)** - 基于多态性贝叶斯分型模型的变异检测 [ [Nature Biotechnology-2021](https://www.nature.com/articles/s41587-021-00861-3) ]

#### 结构变异检测

- **[Delly](https://github.com/dellytools/delly)** - 整合paired-end和split-read分析的结构变异识别[ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/22962449) ]
- **[lumpy](https://github.com/arq5x/lumpy-sv)** - 基于概率框架检测结构变异 [ [paper-2014](https://link.springer.com/article/10.1186/gb-2014-15-6-r84) ]
- **[manta](https://github.com/Illumina/manta)** - 从双端比对数据中检测结构变异和Indel [ [paper-2015](https://pubmed.ncbi.nlm.nih.gov/26647377) ]
- **[gridss](https://github.com/PapenfussLab/gridss)** - 基因组重排检测工具集 [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/29097403) ]
- **[smoove](https://github.com/brentp/smoove)** - 结构变异检测，基因分型
- **[cnvkit](https://github.com/etal/cnvkit)** - 靶向DNA测序拷贝数变异检测 [ [paper-2016](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004873 ) ]

### BAM文件工具

- **[samtools](https://github.com/samtools/samtools)** :thumbsup:- 操作高通量测序数据的工具箱 [ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19505943) | [web](http://htslib.org) ]
- **[bamtools](https://github.com/pezmaster31/bamtools)** - 处理BAM文件工具集 [ [paper-2011](https://academic.oup.com/bioinformatics/article/27/12/1691/255399) ]
- **[bam toolbox](https://github.com/AndersenLab/bam-toolbox)** MtDNA:Nuclear Coverage; BAM Toolbox can output the ratio of MtDNA:nuclear coverage, a proxy for mitochondrial content.
- **[mergesam](https://github.com/DarwinAwardWinner/mergesam)** - 自动SAM/BAM文件转换
- **[mosdepth](https://github.com/brentp/mosdepth)** - WGS，WES，pannel快速BAM/CRAM测序深度计算 [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/29096012/) ]
- **[SAMstat](https://github.com/TimoLassmann/samstat)** - SAM/BAM文件统计 [ [paper-2010](https://academic.oup.com/bioinformatics/article/27/1/130/201972) | [web](http://samstat.sourceforge.net) ]
- **[Somalier](https://github.com/brentp/somalier)** - BAMs/CRANs/VCFs/GVCFs 快速样本交换及相关性检查 [ [paper-2020](https://pubmed.ncbi.nlm.nih.gov/32664994) ]
- **[Telseq](https://github.com/zd1/telseq)** - 从全基因组测序数据中估计端粒长度 [ [paper-2014](https://academic.oup.com/nar/article/42/9/e75/1249448) ]
- **[sambamba](https://github.com/biod/sambamba)**:thumbsup: D语言编写的sam/bam处理工具，markdup等操作较samtools快 [ [Bioinformatics-2015](https://academic.oup.com/bioinformatics/article/31/12/2032/214758) ]
- **[streammd](https://github.com/delocalizer/streammd)** - 基于Bloom filter的单遍概率性重复标记工具，直接消费qname分组的SAM输入流（如`bwa mem`的输出），重复读段置SAM FLAG `0x400`；默认比Picard MarkDuplicates快约5倍，4 GiB内存可处理约10亿模板 [ [paper-2023](https://doi.org/10.1093/bioinformatics/btad181) ]

### VCF文件工具

- **[bcftools](https://github.com/samtools/bcftools)**:thumbsup: - VCF文件操作的工具及 变异检测[ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/26826718) | [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28205675) | [web](http://samtools.github.io/bcftools) ]
- **[vcfanno](https://github.com/brentp/vcfanno)** - 使用VCFs/BEDs/tabixed文件注释VCF [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27250555) ]
- **[vcflib](https://github.com/vcflib/vcflib)** - 解析和操作VCF文件的C++库
- **[vcftools](https://github.com/vcftools/vcftools)** - VCF操作和统计(比如连锁不平衡，等位基因频率，Fst)[ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21653522) ]

### GFF/BED文件工具

- **[AGAT](https://github.com/NBISweden/AGAT)** - 处理GTF/GFF格式基因注释文件工具集[ [web](https://agat.readthedocs.io/en/latest/?badge=latest) ]
- **[gffutils](https://github.com/daler/gffutils)** - GFF和GTF文件操作工具及相互转换[ [web](http://daler.github.io/gffutils) ]
- **[BEDOPS](https://github.com/bedops/bedops)** - 快速，高度可扩展且方便并行处理的基因组分析工具 [ [paper-2012](https://academic.oup.com/bioinformatics/article/28/14/1919/218826) ]
- **[Bedtools2](https://github.com/arq5x/bedtools2)** - 基因组分析的“瑞士军刀” [ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/20110278) | [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25199790) | [web](https://bedtools.readthedocs.io) ]

### 变异模拟

- **[Bam Surgeon](https://github.com/adamewing/bamsurgeon)** -在已有`.bam`文件中添加变异，用于变异检测工具测试 [ [web](https://popmodels.cancercontrol.cancer.gov/gsr/packages/bamsurgeon) ]
- **[wgsim](https://github.com/lh3/wgsim)** - **Comes with samtools!** - 测序数据模拟 [ [web](https://popmodels.cancercontrol.cancer.gov/gsr/packages/wgsim) ]
- **[NGSNGS](https://github.com/RAHenriksen/NGSNGS)** - 多线程二代测序数据模拟器，可模拟现代DNA与古DNA、单端/双端数据，支持从FASTA/FASTQ/`bam`输入建库，输出可直接给下游比对流程 [ [paper-2023](https://doi.org/10.1093/bioinformatics/btad041) ]

### 变异注释

- **[SIFT](https://github.com/teamdfir/sift)** - 预测氨基酸替换是否影响蛋白质功能 [ [paper-2003](https://pubmed.ncbi.nlm.nih.gov/12824425) | [web](http://sift.jcvi.org) ]
- **[SnpEff](https://github.com/pcingola/SnpEff)** - 遗传变异注释及效果预测工具箱 [ [paper-2012](https://www.tandfonline.com/doi/full/10.4161/fly.19695) | [web](https://pcingola.github.io/SnpEff) ]
- **[SpliceAI](https://github.com/Illumina/SpliceAI)** - 预测遗传变异对剪切的影响[ [Cell-2020 ](https://linkinghub.elsevier.com/retrieve/pii/S0092867418316295) ]
- **[Ensembl VEP](https://anaconda.org/bioconda/ensembl-vep)** - 预测变异(SNP、插入、缺失、CNV或结构变异)对基因、转录本、蛋白序列以及调控区域的影响 [ [paper-2016](https://doi.org/10.1186/s13059-016-0974-4) | [web](http://www.ensembl.org/info/docs/tools/vep/index.html) ]
- **[vep-rs](https://github.com/natera-open-source/vep-rs)** :thumbsup: - 用`Rust`从零重写的Ensembl VEP，沿用VEP的输入/参数、后果术语与输出格式，可"drop-in"替换；缓存需用`--json_cache`指向`vep-cache-builder`（或转换Perl VEP缓存）生成的目录，注释速度比Perl实现快约2个数量级，单染色体峰值内存不超过2.4 GB [ [paper-2026](https://doi.org/10.64898/2026.09.22.753614) ]
- **[fastVEP](https://github.com/Huang-lab/fastVEP)** - `Rust`编写的高性能变异效应预测器，对标Ensembl VEP与Illumina Nirvana；零外部依赖、单二进制分发、内存占用极低，单线程注释人类WGS比VEP v115.1快约23倍，但在结构变异上一致性远不如VEP [ [paper-2026](https://www.biorxiv.org/content/10.64898/2026.04.14.718452v1) | [web](https://fastvep.org) ]
- **[ANNOVAR](https://annovar.openbioinformatics.org/en/latest/)** - 遗传变异注释工具，可预测变异对基因、转录本和调控元件的影响，支持自定义数据库整合 [ [paper-2010](https://doi.org/10.1093/nar/gkq603) | [web](https://annovar.openbioinformatics.org/en/latest/) ]

### Python包

#### 数据

- **[cruzdb](https://github.com/brentp/cruzdb)** - Python访问USCC数据库 [ [paper-2013](https://academic.oup.com/bioinformatics/article/29/23/3003/248468) ]
- **[pyensembl](https://github.com/openvax/pyensembl)** - Python访问Ensembl数据库 [ [web](https://pyensembl.readthedocs.io/en/latest/pyensembl.html) ]
- **[bioservices](https://github.com/cokelaer/bioservices)** - Python访问生物Web服务，如KEGG, BLAST [ [paper-2013](https://academic.oup.com/bioinformatics/article/29/24/3241/194040) | [web](http://bioservices.readthedocs.io) ]

#### 工具

- **[cyvcf](https://github.com/arq5x/cyvcf)** -  [pyVCF](https://github.com/jamescasbon/PyVCF) 使用Cython加速版本
- **[cyvcf2](https://github.com/brentp/cyvcf2)** - Cython + HTSlib == 快速解析VCF，比pyVCF还快 [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28165109) | [web](https://brentp.github.io/cyvcf2) ]
- **[polars-bio](https://github.com/biodatageeks/polars-bio)** - 在Polars DataFrame上实现极速基因组区间操作和基因组文件格式读写的Python库 [ [paper-2025](https://doi.org/10.1093/bioinformatics/btaf640) | [web](https://biodatageeks.org/polars-bio/) ]
- **[pyBedTools](https://github.com/daler/pybedtools)** - Python封装的bedtools](https://github.com/arq5x/bedtools). [ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21949271) | [web](http://daler.github.io/pybedtools) ]
- **[pyfaidx](https://github.com/mdshw5/pyfaidx)** - Python访问fasta文件
- **[pysam](https://github.com/pysam-developers/pysam)** - Python封装的[samtools](https://github.com/samtools/samtools). [ [web](https://pysam.readthedocs.io/en/latest/api.html) ]
- **[pyVCF](https://github.com/jamescasbon/PyVCF)** - Python解析VCF文件 [ [web](http://pyvcf.readthedocs.org/en/latest/index.html) ]
- **[Scanpy](https://github.com/scverse/scanpy)** - 用于分析单细胞基因表达数据的可扩展工具包，涵盖预处理、可视化、聚类和轨迹推断 [ [paper-2018](https://doi.org/10.1186/s13059-017-1382-0) | [web](https://scanpy.readthedocs.io) ]

### 组装


- **[SPAdes](https://github.com/ablab/spades)** - SPAdes (St. Petersburg genome assembler) 原核生物基因组组装/分析工具集
- **[SKESA](https://github.com/ncbi/SKESA)** - SKESA，微生物基因组序列重头组装。使用保守的启发式方法，在基因组中的重复区域创建断点。 这会生成高质量的序列，而不会显著影响连续性。
- **[Minimap2](https://github.com/lh3/minimap2)** - 用于基因组序列和剪接核苷酸序列的双序列比对工具，可进行组装到组装的比对，支持gzip压缩的FASTQ、FASTA格式，也能寻找长读长之间的重叠
- **[D-GENIES](https://dgenies.toulouse.inra.fr/)** - **D**ot plot large **Gen**omes in an **I**nteractive, **E**fficient and **S**imple way，用于大型基因组比对的在线工具，可交互式改进dot plot可视化。也可作为minimap2的扩展，上传PAF(Pairwise mApping Format)或MAF(Multiple Alignment File)比对结果到D-GENIES

### 长读长测序

#### 组装

- **[canu](https://github.com/marbl/canu)** - 单分子序列组装工具，大小基因组均适用
- **[flye](https://github.com/fenderglass/Flye)** - 适用repeat graph进行单分子测序重头组装
- **[hifiasm](https://github.com/chhylp123/hifiasm)** - haplotype-resolved de novo assembler for PacBio HiFi reads
- **[wtdbg2](https://github.com/ruanjue/wtdbg2)** - 基于模糊Bruijn graph方法的长读长组装

### 注释

- **[Prokka](https://github.com/tseemann/prokka)** - 快速进行原核基因组注释，Prokka是微生物基因组注释最常用的工具之一。
- **[Bakta](https://github.com/oschwengers/bakta)** - Bakta 是一种用于对细菌基因组和质粒进行快速和标准化注释的工具。 它以 JSON 和生物信息学标准文件格式提供dbxref -rich和 sORF 的注释，用于自动下游分析。
- **[Bacannot](https://github.com/fmalmeida/bacannot)** - 基于Nextflow的细菌基因组注释的流程 [ [web](https://bacannot.readthedocs.io/en/latest/?badge=latest) ]


## 可视化

### 基因组浏览器/基因图

下列工具可用来可视化基因组数据，包括DNA-seq，RNA-seq，ChIP-seq，变异等。

- **[Squiggle](https://github.com/Lab41/squiggle)** - DNA序列可视化 [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30247632) | [web](https://squiggle.readthedocs.io/en/latest/) ]
- **[biodalliance](https://github.com/dasmoth/dalliance)** - 轻量级基因组浏览器，支持多种经典的基因组文件格式，比如bigWig，BAM，VCF等[ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21252075) | [web](http://www.biodalliance.org) ]
- **[BioJS](https://github.com/biojs/biojs)** - 收录生物学数据可视化的JS组件库 [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25075290/) | [web](http://biojs.net/) ]
- **[Circleator](https://github.com/jonathancrabtree/Circleator)** - 使用BioPerl和SVG环形可视化基因组相关数据 [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25075113) ]
- **[DNAism](https://github.com/drio/dnaism)** - 基于D3的DNA数据可视化JS库 [ [paper-2016](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0891-2) | [web](http://drio.github.io/dnaism/) ]
- **[IGV js](https://github.com/igvteam/igv)**:thumbsup: - 基于Java的基因组浏览器，同时提供JS版本。支持多种数据格式 [ [paper-2019](https://pubmed.ncbi.nlm.nih.gov/31099383) | [web](https://software.broadinstitute.org/software/igv) ]
- **[Island Plot](https://github.com/lairdm/islandplot)** - 基于D3的基因组浏览器[ [paper-2015](https://pubmed.ncbi.nlm.nih.gov/25916842/) ]
- **[JBrowse](https://github.com/GMOD/jbrowse)** - 通过插件和track个性化高度定制的基因组浏览器 [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27072794) | [web](http://jbrowse.org/) ]
- **[PHAT](https://github.com/chgibb/PHAT)** - 病原-宿主可视化分析工具 [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30561651) | [web](https://chgibb.github.io/PHATDocs) ]
- **[pileup.js](https://github.com/hammerlab/pileup.js)** - 可交互，高度定制的基于web的基因组浏览器JS库 [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27153605) ]
- **[scribl](https://github.com/chmille4/Scribl)** - HTML5 canvas 基因组图形库 [ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/23172864) | [web](http://chmille4.github.io/Scribl) ]
- **[pyGenomeTracks](https://github.com/deeptools/pyGenomeTracks)** - Python绘制基因组浏览器track
- **[WashU EpiGenomoe Browser](https://github.com/epgg/eg)** - 表观基因组浏览器 [ [Nucleid Acids Research 2019](https://academic.oup.com/nar/article/47/W1/W158/5511467) | [web](https://epigenomegateway.wustl.edu/) ]

### Circos相关

- **[Circos](https://github.com/vigsterkr/circos)** - 基因组数据环形可视化Perl包 [ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19541911) | [web](http://circos.ca) ]
- **OmicCircos** - 组学数据环形可视化R包 [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/24526832) | [web](http://www.bioconductor.org/packages/release/bioc/html/OmicCircos.html) ]
- **J-Circos** - Circos Java版 [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25540184) | [web](http://www.australianprostatecentre.org/research/software/jcircos) ]
- **[circlize](https://github.com/jokergoo/circlize)**:thumbsup: - Circos R包 [ [paper-2014](https://www.ncbi.nlm.nih.gov/pubmed/24930139) ]
- **[fujiplot](https://github.com/mkanai/fujiplot)** - GWAS结果Circos展示 [ [paper-2018](https://www.nature.com/articles/s41588-018-0047-6) ]
- **[circosJS](https://github.com/nicgirault/circosJS)**:thumbsup: - 基于d3的Circos JS库

### 染色体可视化

- **[ideogram](https://github.com/eweitz/ideogram)** - 染色体可视化的JS库
- **[karyoploteR](https://github.com/bernatgel/karyoploteR)** - 可视化染色体/track的R包

### Venn图

- **[UpSetR](https://github.com/hms-dbmi/UpSetR)**:thumbsup: - 另一种展示集合交并集的方式 [ [Bioinformatics-2017](https://academic.oup.com/bioinformatics/article/33/18/2938/3884387) ]

## 数据库访问

- [Entrez Direct: E-utilities on the UNIX command line](http://www.ncbi.nlm.nih.gov/books/NBK179288/) - UNIX命令行工具访问NCBI数据库

## 资源

### 成为一个生物信息学家

- [什么是生物信息学家(英文)](http://blog.fejes.ca/?p=2418)
- [生物信息学课程指南：定义核心竞争力(英文)](http://www.ploscompbiol.org/article/info:doi%2F10.1371%2Fjournal.pcbi.1003496)
- [读生物信息学/计算生物学博士/博士后的N个理由(英文)](http://caseybergman.wordpress.com/2012/07/31/top-n-reasons-to-do-a-ph-d-or-post-doc-in-bioinformaticscomputational-biology/)
- [生物信息学家聚会交流的10步指南(英文)](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-1-104) - 这是当领域外的人问"你在做什么？"介绍专业的概念的一步步指南。
- [生物信息学简史 (2039年)(英文)](https://www.youtube.com/watch?v=uwsjwMO-TEA) - C. Titus Brown回归2039年以来的生物信息学，演讲笔记参考[这里](http://ivory.idyll.org/blog/2014-bosc-keynote.html).
- [再见生物信息学(英文)](https://madhadron.com/science/farewell_to_bioinformatics.html) - 对生物信息学的批判观点
- [著名生物信息学系列采访](http://www.acgt.me/blog/2014/3/25/101-questions-a-new-series-of-interviews-with-notable-bioinformaticians) - 著名生物信息学家采访，对当今生物信息学研究现状的看法及职业规划有帮助
- [开源的生物信息学社会大学](https://github.com/ossu/bioinformatics) - 生物信息学免费课程
- [Rosalind](http://rosalind.info/) - Rosalind是一个通过解决问题学习生物信息学的平台
- [生物信息学101计划课件资源](https://bis.zju.edu.cn/bioinfo101/ppt_resources/) :thumbsup: - 教育部生物科学"101计划"《生物信息学（含生物统计学）》核心课程（浙江大学陈铭、上海交通大学吕晖牵头，33所高校参与）的配套课件，共13章，覆盖生物统计学基础、深度学习与人工智能、生物信息资源、序列比对、基因组学与宏基因组学、转录组学、转录调控与表观遗传、蛋白质与代谢组学、表型组学、系统生物学、生物信息学应用与编程，提供师资培训版PPT下载，中文，适合系统入门与教师备课
- [生物信息学算法(英文)](https://www.bioinformaticsalgorithms.org/read-the-book) - Phillip Compeau和Pavel Pevzner编写的教材，前五章可免费在线阅读
- [写给孤独生物信息学家的指南(英文)](http://www.opiniomics.org/a-guide-for-the-lonely-bioinformatician/) - 本指南针对生物信息学家的职业发展。
- [生物信息学简史](https://doi.org/10.1093/bib/bby063)

### 其它Awesome Bioinformatics

- [Awesome-alternative-splicing](https://github.com/HussainAther/awesome-alternative-splicing) - 可变剪切软件，数据库，工具的资源库
- [Awesome AI-based Protein Design](https://github.com/opendilab/awesome-AI-based-protein-design) - AI蛋白质设计相关的研究论文集

### 测序

- [下一代测序技术 - Elaine Mardis (2014)](https://youtu.be/6Is3W7JkFp8) [1:34:35] - 二代和三代测序技术的综述，以及在癌症研究中的应用
- [Annotated bibliography of \*Seq assays](https://liorpachter.wordpress.com/seq/) - 约100篇论文列表，涉及从转录到可转座因子发现的各种测序技术
- [For all you seq... (PDF)](http://www.illumina.com/content/dam/illumina-marketing/documents/applications/ngs-library-prep/ForAllYouSeqMethods.pdf) (3456x5471):thumbsup: - Illumina提供的测序远离示意图，涵盖蛋白质相互作用，RNA转录，RNA-protein相互作用，低丰度RNA检测，RNA修饰，RNA结构，DNA重排，低丰度DNA检测，表观遗传学，DNA-蛋白质互作。

### RNA-Seq

- [RNA-seq的综述文章 (Biostars)](https://www.biostars.org/p/52152/) - 包括RNA-seq和分析方法的开创性文章
- [Informatics for RNA-seq: A web resource for analysis on the cloud](https://github.com/griffithlab/rnaseq_tutorial) - 使用亚马逊云服务分析RNA-seq的教育资源，包括数据准备，预处理，差异表达， 异构体发现，数据可视化和解释
- [RNA-seqlopedia](http://rnaseq.uoregon.edu/) - RNA-seqlopedia提供RNA-seq综述，以及成功进行RNA-seq实验必要选择
- [A survey of best practices for RNA-seq data analysis](http://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8) - RNA-seq计算分析路线图，包括挑战/障碍和注意事项，以及如何整合RNA-seq数据和其它数据类型
- [Stories from the Supplement](https://www.youtube.com/watch?v=5NiFibnbE8o) [46:39] - Lior Pachter分享著名RNA-seq分析软件CuffDiff和Cufflinks背后的故事及方法学
- [RNA-seq生物信息学工具](https://en.wikipedia.org/wiki/List_of_RNA-Seq_bioinformatics_tools) - RNA-seq分析工具Wiki列表，包括质控，比对，可变剪切分析和可视化
- [RNA-seq Analysis](https://github.com/crazyhottommy/RNA-seq-analysis) - [@crazyhottommy](https://github.com/crazyhottommy) 关于RNA-seq分析各步骤及注意事项的笔记

### ChIP-Seq

- [ChIP-seq analysis notes from Tommy Tang](https://github.com/crazyhottommy/ChIP-seq-analysis) - ChIP-seq数据分析资源，包括文章，方法，软件和分析步骤

### YouTube频道和播放列表

- [Current Topics in Genome Analysis 2016](https://www.genome.gov/12514288/current-topics-in-genome-analysis-2016-course-syllabus-handouts-and-videos/) - NIH举办了精彩的十四讲系列讲座，内容涉及基因组学从序列分析到测序技术。
- [GenomeTV](https://www.youtube.com/user/GenomeTV) - GnomeTV是NHGRI收录演讲，纪录片，会议的官方视频资源，包括基因组研究，问题和临床应用
- [Leading Strand](https://www.youtube.com/user/LeadingStrand) - 冷泉港(CSHL)会议主题演讲
- [Genomics, Big Data and Medicine Seminar Series](https://www.youtube.com/playlist?list=PLqLDR0CTP9_pboZCk6gR9Zn4kW7h9XWJI) - 关于基因组学，大数据，医药的系列研讨会
- [Rafael Irizarry's Channel](https://www.youtube.com/user/RafalabChannel/videos) - Rafael Irizarry关于基因组统计学的学术报告
- [NIH VideoCasting and Podcasting](https://www.youtube.com/user/nihvcast) - NIH直播，不仅是基因组学和生物信息学，还包括其它特定领域使用生物信息学和基因组学的精彩演讲
- [生物信息学算法课程视频(英文)](https://www.bioinformaticsalgorithms.org/lecture-videos) - 配套Phillip Compeau和Pavel Pevzner《Bioinformatics Algorithms》教材的免费课程视频

### 博客

- [ACGT](http://www.acgt.me/) - Keith Bradnam的博客，主要关于生物学，基因组学以及生物信息学的看法
- [Opiniomics](http://www.opiniomics.org/) - Mick Watson的博客，主要关于生物信息学，基因组学和生物学
- [Bits of DNA](https://liorpachter.wordpress.com/) - Lior Pachter的博客，主要关于计算生物学的综述和评论
- [it is NOT junk](http://www.michaeleisen.org/blog/) - Michael Eisen的博客，主要关于基因组学，DNA，进化
- [#!/perl/bioinfo](https://bioinfoperl.blogspot.com) - EEAD-CSIC计算与结构生物学组用西班牙语和英语撰写的博客，内容涉及植物基因组学、计算与结构生物学的方法和代码

### 其它

- [Leek group基因组文献推荐阅读](https://github.com/jtleek/genomicspapers/) - 专家校正的基因组文献帮助快速入门基因组学，RNA-seq，基因组统计学，软件开发
- [在线计算生物学课程](https://doi.org/10.1371/journal.pcbi.1003662) - 本文介绍了数百个免费视频课程，对那些希望扩展其生物信息学和计算生物学知识的人们来说是必不可少的。这些课程分为11个学科领域，并附有评论和职业建议。
- [Perl是如何拯救人类基因组计划(英文)](http://www.foo.be/docs/tpj/issues/vol1_2/tpj0102-0001.html) - Lincoln D. Stein的一则轶闻，关于人类基因组计划中Perl语言的重要性
- [Nature Biotechnology/PLos Computational Biology科普文章(英文)](https://liacs.leidenuniv.nl/~hoogeboomhj/mcb/nature_primer.html) - Nature Biotechnology和PLos Computational Biology上关于计算生物学和生物信息学各种方法的入门的科普文章链接
- [PeerJ生物信息软件工具集](https://peerj.com/collections/45-bioinformatics-software/) - Keith Crandall and Claus White整理的PeerJ上有趣，创新及香瓜你的生物信息学工具
- [Biological Modeling](https://biologicalmodeling.org/) - 生物系统建模的免费在线课程，涵盖图灵斑图、转录因子网络基序、细菌趋化性、冠状病毒刺突蛋白以及白细胞图像分类

## 在线社区

- [Bioinformatics (on Discord)](https://discord.com/invite/3uxbPns) - 生物信息学Discord服务器
- [r-bioinformatics](https://www.reddit.com/r/bioinformatics/comments/7ndwm1/rbioinformatics_slack_channel_and_an_open_call/) - r/bioinformatics官方Slack
- [BioinformaticsGRX](https://bioinformaticsgrx.es/) - 位于西班牙格拉纳达的生物信息学家社区
- [Comunidad de Desarolladores de Software en Bioinformática](https://comunidadbioinfo.github.io/) - 以拉丁美洲为中心的生物信息学家社区
- [COMBINE](https://combine.org.au/) - 澳大利亚生物信息学学生团体

## 许可

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)