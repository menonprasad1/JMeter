LogAnalyzer @Author: Prasad Menon
======

LogAnalyzer is a tool written using awk to analyze the JMeter Logs.
Loading the logs into the JMeter Plugins can be tortourous if the output file generated is too large.
This LogAnalyzer will generate all the basic statistics including Percentiles, error rate, throughput etc.

Zlib_v1.1
======
This is a bean shell sampler. This reads a file containing 1 or many JSON records, changes the timestamp in the records. It then compresses this file in a ZLIB format and writes it to a disk. An http sampler then picks this file and sends this to a logger.
