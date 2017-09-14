#ssDNA工作记录
## QC
通过文章《Targeted sequencing of both DNA strands barcoded and captured individually by RNA probes to identify genome-wide ultra-raremutations》确定主要的QC指标。

QC指标模板文件名为```Quality control_20170914.docx```

##BWA aln和mem
[Teaser] (http://teaser.cibiv.univie.ac.at/reports/8dc974f7ce99f6958012619c052e5597/index.html#section4) 、[Biostars](https://www.biostars.org/p/117225/)等的讨论话题，以及BWA软件说明，提示mem算法对于大于70bp的reads，其比对效果远优于另外两种算法。

本次测试还是用BWA mem比较好。

##DS技术中barcode

