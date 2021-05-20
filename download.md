# 5-18-2021 epi-line floral stem data is ready for download
#downloaded to /data/users/xzy50/epi_line_floral_stem_5_18_2021

`
wget -r --user=X202SC21033369-Z01-F003 --password=XXXXXXXX ftp://X202SC21033369-Z01-F003:0r3p2rh0@usftp21.novogene.com:21/raw_data/
wget -r --user=X202SC21033369-Z01-F003 --password=XXXXXXXX ftp://X202SC21033369-Z01-F003:0r3p2rh0@usftp21.novogene.com:21/checkSize.xls
wget -r --user=X202SC21033369-Z01-F003 --password=XXXXXXXX ftp://X202SC21033369-Z01-F003:0r3p2rh0@usftp21.novogene.com:21/report/X202SC21033369-Z01-F003_final_20210513032544.zip 
`
# check the md5
# orignal md5 
`
-bash-4.2$ cat epi24SP1/MD5.txt 
7264e3fe7e6dbaaa30917f30618b4738  epi24SP1_1.fq.gz
b492af143ce8960c376a0f35cccdf79c  epi24SP1_2.fq.gz
-bash-4.2$ cat epi24SP2/MD5.txt 
713b22aebec981d4cad2808e2b113076  epi24SP2_1.fq.gz
14587d1b48c6ee9073b16e51d99e1871  epi24SP2_2.fq.gz
-bash-4.2$ cat epi24SP3/MD5.txt 
d1e6ecd3b0c71514d681ba8bf2276f6e  epi24SP3_1.fq.gz
1416192657998e4a18e7495d2a7c3a06  epi24SP3_2.fq.gz
-bash-4.2$ cat epi8SP1/MD5.txt 
bee08857dc8c1b61f1013822709428a6  epi8SP1_1.fq.gz
2c70182e0b18dfacf427cf4341a1832a  epi8SP1_2.fq.gz
-bash-4.2$ cat epi8SP2/MD5.txt 
b813c709dd02f7a0715cf7a61b56a793  epi8SP2_1.fq.gz
a58a666efb7ea1e6a4d9d466461b7fb3  epi8SP2_2.fq.gz
-bash-4.2$ cat epi8SP3/MD5.txt 
61885275da25b37fb3716698b964690d  epi8SP3_1.fq.gz
629c7eac3a5b5633566ce4bb2d64ea3d  epi8SP3_2.fq.gz
-bash-4.2$ cat MemSP1/MD5.txt 
707b1304184f179d133504e662b79aff  MemSP1_1.fq.gz
87542eaa956f921314201231259da563  MemSP1_2.fq.gz
-bash-4.2$ cat MemSP2/MD5.txt 
3b3c83bae114a49fb22d3bfeb1626618  MemSP2_1.fq.gz
ca5b72f3ee16d6ae0b8fa8c96d0061ff  MemSP2_2.fq.gz
-bash-4.2$ cat MemSP3/MD5.txt 
ad27741d02e556a5fd1550561760b02c  MemSP3_1.fq.gz
9f5fbce968d838ca168dca3692928be0  MemSP3_2.fq.gz
-bash-4.2$ cat WTSP1/MD5.txt 
72e4235b4a2dd7ff30bd32054c67886b  WTSP1_1.fq.gz
03b4ca516479b134970186ab8f99ac1d  WTSP1_2.fq.gz
-bash-4.2$ cat WTSP2/MD5.txt 
9c8f7a6ebf6115381dea850e2fce0047  WTSP2_1.fq.gz
d5e976f7e1829e7463fef9669bb119b1  WTSP2_2.fq.gz
-bash-4.2$ cat WTSP3/MD5.txt 
ccc8af1d6377db93fcb0aaa8b1005566  WTSP3_1.fq.gz
20710a177a9b2b73784c13de6b93e7db  WTSP3_2.fq.gz
`

# check the new md5
`
-bash-4.2$ md5sum epi24SP1/epi24SP1_1.fq.gz 
7264e3fe7e6dbaaa30917f30618b4738  epi24SP1/epi24SP1_1.fq.gz
-bash-4.2$ md5sum epi24SP1/epi24SP1_2.fq.gz 
b492af143ce8960c376a0f35cccdf79c  epi24SP1/epi24SP1_2.fq.gz
-bash-4.2$ md5sum epi24SP2/epi24SP2_1.fq.gz 
713b22aebec981d4cad2808e2b113076  epi24SP2/epi24SP2_1.fq.gz
-bash-4.2$ md5sum epi24SP2/epi24SP2_2.fq.gz 
14587d1b48c6ee9073b16e51d99e1871  epi24SP2/epi24SP2_2.fq.gz
d1e6ecd3b0c71514d681ba8bf2276f6e  epi24SP3/epi24SP3_1.fq.gz
-bash-4.2$ md5sum epi24SP3/epi24SP3_2.fq.gz 
1416192657998e4a18e7495d2a7c3a06  epi24SP3/epi24SP3_2.fq.gz

-bash-4.2$ md5sum epi8SP1/epi8SP1_1.fq.gz 
bee08857dc8c1b61f1013822709428a6  epi8SP1/epi8SP1_1.fq.gz
-bash-4.2$ md5sum epi8SP1/epi8SP1_2.fq.gz 
2c70182e0b18dfacf427cf4341a1832a  epi8SP1/epi8SP1_2.fq.gz
-bash-4.2$ md5sum epi8SP2/epi8SP2_1.fq.gz 
b813c709dd02f7a0715cf7a61b56a793  epi8SP2/epi8SP2_1.fq.gz
-bash-4.2$ md5sum epi8SP2/epi8SP2_2.fq.gz 
a58a666efb7ea1e6a4d9d466461b7fb3  epi8SP2/epi8SP2_2.fq.gz
-bash-4.2$ md5sum epi8SP3/epi8SP3_1.fq.gz 
61885275da25b37fb3716698b964690d  epi8SP3/epi8SP3_1.fq.gz
-bash-4.2$ md5sum epi8SP3/epi8SP3_2.fq.gz 
629c7eac3a5b5633566ce4bb2d64ea3d  epi8SP3/epi8SP3_2.fq.gz

-bash-4.2$ md5sum MemSP1/MemSP1_1.fq.gz
707b1304184f179d133504e662b79aff  MemSP1/MemSP1_1.fq.gz
-bash-4.2$ md5sum MemSP1/MemSP1_2.fq.gz
87542eaa956f921314201231259da563  MemSP1/MemSP1_2.fq.gz
-bash-4.2$ md5sum MemSP2/MemSP2_1.fq.gz
3b3c83bae114a49fb22d3bfeb1626618  MemSP2/MemSP2_1.fq.gz
-bash-4.2$ md5sum MemSP2/MemSP2_2.fq.gz
ca5b72f3ee16d6ae0b8fa8c96d0061ff  MemSP2/MemSP2_2.fq.gz
-bash-4.2$ md5sum MemSP3/MemSP3_1.fq.gz
ad27741d02e556a5fd1550561760b02c  MemSP3/MemSP3_1.fq.gz
-bash-4.2$ md5sum MemSP3/MemSP3_2.fq.gz
9f5fbce968d838ca168dca3692928be0  MemSP3/MemSP3_2.fq.gz

-bash-4.2$ md5sum WTSP1/WTSP1_1.fq.gz
72e4235b4a2dd7ff30bd32054c67886b  WTSP1/WTSP1_1.fq.gz
-bash-4.2$ md5sum WTSP1/WTSP1_2.fq.gz
03b4ca516479b134970186ab8f99ac1d  WTSP1/WTSP1_2.fq.gz
-bash-4.2$ md5sum WTSP2/WTSP2_1.fq.gz
9c8f7a6ebf6115381dea850e2fce0047  WTSP2/WTSP2_1.fq.gz
-bash-4.2$ md5sum WTSP2/WTSP2_2.fq.gz
d5e976f7e1829e7463fef9669bb119b1  WTSP2/WTSP2_2.fq.gz
-bash-4.2$ md5sum WTSP3/WTSP3_1.fq.gz
ccc8af1d6377db93fcb0aaa8b1005566  WTSP3/WTSP3_1.fq.gz
-bash-4.2$ md5sum WTSP3/WTSP3_2.fq.gz
20710a177a9b2b73784c13de6b93e7db  WTSP3/WTSP3_2.fq.gz
`
