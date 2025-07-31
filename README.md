# AHBench
This repo provide a dependency upgraded version of AHBench. 

 AHBench is a tool provided by Alibaba for testing hbase performance. official link: https://help.aliyun.com/zh/hbase/user-guide/use-shell-to-test-performance
 
# Why this repo?
- AHBench use old and deprecated versions of ycsb and hbase driver. some new hbase compatbile database is not fully compatible with drivers like hbase-client 1.1.9. so we need **UPGRADE**

# modification
- upgrade ycsb to 0.17 (latest public version)
- upgrade hbase client to 2.6.3 (latest public version)

# Usage
All usages are the same with the original AHBench tool. Enjoy testing. 
Ref to the original Aliyun article for usage. 
https://help.aliyun.com/zh/hbase/user-guide/use-shell-to-test-performance
