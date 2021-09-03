>####################
> author: Jade DC
> title: common tricks of command line
> date: 2021年 8月27日 星期五 08时05分57秒 UTC
> email: jadebetter8092@gmail.com
>####################
# date format: year-mounth-day
```bash
date +%F
```
# traslate lall uppercase letters to lowercase
```bash
tr A-Z a-z 
```
# count fastq(.gz) reads
- fastq.gz
echo $(zcat <fastq.gz> | wc -l)/4 | bc
- fastq
echo $(cat <fastq> | wc -l)/4 | bc
