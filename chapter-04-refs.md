Designing Data-Intensive Applications, 2nd edition
==================================================

Chapter 4 References
--------------------

1. Nikolay Samokhvalov.
 [How partial, covering, and multicolumn indexes may slow down UPDATEs in PostgreSQL](https://postgres.ai/blog/20211029-how-partial-and-covering-indexes-affect-update-performance-in-postgresql).
 *postgres.ai*, October 2021.
 Archived at [perma.cc/PBK3-F4G9](https://perma.cc/PBK3-F4G9)

1. Goetz Graefe.
   [Modern B-Tree Techniques](https://w6113.github.io/files/papers/btreesurvey-graefe.pdf).
   *Foundations and Trends in Databases*, volume 3, issue 4, pages 203–402, August 2011.
   [doi:10.1561/1900000028](https://doi.org/10.1561/1900000028)

1. Evan Jones.
 [Why databases use ordered indexes but programming uses hash tables](https://www.evanjones.ca/ordered-vs-unordered-indexes.html). *evanjones.ca*, December 2019.
 Archived at [perma.cc/NJX8-3ZZD](https://perma.cc/NJX8-3ZZD)

1. Branimir Lambov.
 [CEP-25: Trie-indexed SSTable format](https://cwiki.apache.org/confluence/display/CASSANDRA/CEP-25%3A+Trie-indexed+SSTable+format). *cwiki.apache.org*, November 2022.
 Archived at [perma.cc/HD7W-PW8U](https://perma.cc/HD7W-PW8U).
 Linked Google Doc archived at [perma.cc/UL6C-AAAE](https://perma.cc/UL6C-AAAE)

1. Thomas H. Cormen, Charles E.
   Leiserson, Ronald L. Rivest, and Clifford Stein: *Introduction to Algorithms*, 3rd edition.
   MIT Press, 2009. ISBN: 978-0-262-53305-8

1. Branimir Lambov.
   [Trie Memtables in Cassandra](https://www.vldb.org/pvldb/vol15/p3359-lambov.pdf).
   *Proceedings of the VLDB Endowment*, volume 15, issue 12, pages 3359–3371, August 2022.
   [doi:10.14778/3554821.3554828](https://doi.org/10.14778/3554821.3554828)

1. Dhruba Borthakur.
 [The History of RocksDB](https://rocksdb.blogspot.com/2013/11/the-history-of-rocksdb.html).
 *rocksdb.blogspot.com*, November 2013.
 Archived at [perma.cc/Z7C5-JPSP](https://perma.cc/Z7C5-JPSP)

1. Matteo Bertozzi.
 [Apache HBase I/O – HFile](https://blog.cloudera.com/apache-hbase-i-o-hfile/).
 *blog.cloudera.com*, June 2012.
 Archived at [perma.cc/U9XH-L2KL](https://perma.cc/U9XH-L2KL)

1. Fay Chang, Jeffrey Dean, Sanjay Ghemawat,
 Wilson C. Hsieh, Deborah A. Wallach, Mike Burrows, Tushar Chandra, Andrew Fikes, and Robert E. Gruber.
 [Bigtable: A Distributed Storage System for Structured Data](https://research.google/pubs/pub27898/). At *7th USENIX Symposium on Operating System Design and
 Implementation* (OSDI), November 2006.

1. Patrick O'Neil, Edward Cheng, Dieter Gawlick, and
 Elizabeth O'Neil.
 [The Log-Structured Merge-Tree (LSM-Tree)](https://www.cs.umb.edu/~poneil/lsmtree.pdf).
 *Acta Informatica*, volume 33, issue 4, pages 351–385, June 1996.
 [doi:10.1007/s002360050048](https://doi.org/10.1007/s002360050048)

1. Mendel Rosenblum and John K. Ousterhout.
 [The Design and Implementation of a Log-Structured File System](https://research.cs.wisc.edu/areas/os/Qual/papers/lfs.pdf).
 *ACM Transactions on Computer Systems*, volume 10, issue 1, pages 26–52, February 1992.
 [doi:10.1145/146941.146943](https://doi.org/10.1145/146941.146943)

1. Michael Armbrust, Tathagata Das, Liwen Sun,
 Burak Yavuz, Shixiong Zhu, Mukul Murthy, Joseph Torres, Herman van Hovell, Adrian Ionescu, Alicja
 Łuszczak, Michał Świtakowski, Michał Szafrański, Xiao Li, Takuya Ueshin, Mostafa Mokhtar, Peter
 Boncz, Ali Ghodsi, Sameer Paranjpye, Pieter Senster, Reynold Xin, and Matei Zaharia.
 [Delta Lake: High-Performance ACID Table Storage over Cloud Object Stores](https://vldb.org/pvldb/vol13/p3411-armbrust.pdf). *Proceedings of the VLDB Endowment*, volume 13,
 issue 12, pages 3411–3424, August 2020.
 [doi:10.14778/3415478.3415560](https://doi.org/10.14778/3415478.3415560)

1. Burton H. Bloom.
 [Space/Time Trade-offs in Hash Coding with Allowable Errors](https://people.cs.umass.edu/~emery/classes/cmpsci691st/readings/Misc/p422-bloom.pdf). *Communications of the ACM*,
 volume 13, issue 7, pages 422–426, July 1970.
 [doi:10.1145/362686.362692](https://doi.org/10.1145/362686.362692)

1. Adam Kirsch and Michael Mitzenmacher.
 [Less Hashing, Same Performance: Building a Better Bloom Filter](https://www.eecs.harvard.edu/%7Emichaelm/postscripts/tr-02-05.pdf). *Random Structures & Algorithms*,
 volume 33, issue 2, pages 187–218, September 2008.
 [doi:10.1002/rsa.20208](https://doi.org/10.1002/rsa.20208)

1. Thomas Hurst.
 [Bloom Filter Calculator](https://hur.st/bloomfilter/). *hur.st*, September 2023.
 Archived at [perma.cc/L3AV-6VC2](https://perma.cc/L3AV-6VC2)

1. Chen Luo and Michael J. Carey.
 [LSM-based storage techniques: a survey](https://arxiv.org/abs/1812.07527).
 *The VLDB Journal*, volume 29, pages 393–418, July 2019.
 [doi:10.1007/s00778-019-00555-y](https://doi.org/10.1007/s00778-019-00555-y)

1. Subhadeep Sarkar and Manos Athanassoulis.
 [Dissecting, Designing, and Optimizing LSM-based Data Stores](https://www.youtube.com/watch?v=hkMkBZn2mGs). Tutorial at *ACM International Conference on Management of Data*
 (SIGMOD), June 2022. Slides archived at
 [perma.cc/93B3-E827](https://perma.cc/93B3-E827)

1. Mark Callaghan.
 [Name that compaction algorithm](https://smalldatum.blogspot.com/2018/08/name-that-compaction-algorithm.html). *smalldatum.blogspot.com*, August 2018.
 Archived at [perma.cc/CN4M-82DY](https://perma.cc/CN4M-82DY)

1. Prashanth Rao.
 [Embedded databases (1): The harmony of DuckDB, KùzuDB and LanceDB](https://thedataquarry.com/posts/embedded-db-1/). *thedataquarry.com*, August 2023.
 Archived at [perma.cc/PA28-2R35](https://perma.cc/PA28-2R35)

1. Hacker News discussion.
 [Bluesky migrates to single-tenant SQLite](https://news.ycombinator.com/item?id=38171322).
 *news.ycombinator.com*, October 2023.
 Archived at [perma.cc/69LM-5P6X](https://perma.cc/69LM-5P6X)

1. Rudolf Bayer and Edward M. McCreight.
 [Organization and Maintenance of Large Ordered Indices](https://dl.acm.org/doi/pdf/10.1145/1734663.1734671). Boeing Scientific Research Laboratories, Mathematical and Information Sciences
 Laboratory, report no. 20, July 1970.
 [doi:10.1145/1734663.1734671](https://doi.org/10.1145/1734663.1734671)

1. Douglas Comer.
 [The Ubiquitous B-Tree](https://web.archive.org/web/20170809145513id_/http://sites.fas.harvard.edu/~cs165/papers/comer.pdf). *ACM Computing Surveys*, volume 11, issue 2, pages 121–137, June 1979.
 [doi:10.1145/356770.356776](https://doi.org/10.1145/356770.356776)

1. Alex Miller.
 [Torn Write Detection and Protection](https://transactional.blog/blog/2025-torn-writes).
 *transactional.blog*, April 2025.
 Archived at [perma.cc/G7EB-33EW](https://perma.cc/G7EB-33EW)

1. C. Mohan and Frank Levine.
 [ARIES/IM: An Efficient and High Concurrency Index Management Method Using Write-Ahead Logging](https://ics.uci.edu/~cs223/papers/p371-mohan.pdf). At *ACM
 International Conference on Management of Data* (SIGMOD), June 1992.
 [doi:10.1145/130283.130338](https://doi.org/10.1145/130283.130338)

1. Hironobu Suzuki.
 [The Internals of PostgreSQL](https://www.interdb.jp/pg/). *interdb.jp*, 2017.

1. Howard Chu.
   [LDAP at Lightning Speed](https://buildstuff14.sched.com/event/08a1a368e272eb599a52e08b4c3c779d).
   At *Build Stuff '14*, November 2014.
   Archived at [perma.cc/GB6Z-P8YH](https://perma.cc/GB6Z-P8YH)

1. Manos Athanassoulis, Michael S. Kester,
 Lukas M. Maas, Radu Stoica, Stratos Idreos, Anastasia Ailamaki, and Mark Callaghan.
 [Designing Access Methods: The RUM Conjecture](https://openproceedings.org/2016/conf/edbt/paper-12.pdf). At *19th International Conference on Extending Database Technology* (EDBT), March 2016.
 [doi:10.5441/002/edbt.2016.42](https://doi.org/10.5441/002/edbt.2016.42)

1. Ben Stopford.
 [Log Structured Merge Trees](http://www.benstopford.com/2015/02/14/log-structured-merge-trees/).
 *benstopford.com*, February 2015.
 Archived at [perma.cc/E5BV-KUJ6](https://perma.cc/E5BV-KUJ6)

1. Mark Callaghan.
 [The Advantages of an LSM vs a B-Tree](https://smalldatum.blogspot.com/2016/01/summary-of-advantages-of-lsm-vs-b-tree.html). *smalldatum.blogspot.co.uk*, January 2016.
 Archived at [perma.cc/3TYZ-EFUD](https://perma.cc/3TYZ-EFUD)

1. Oana Balmau, Florin Dinu, Willy Zwaenepoel, Karan
 Gupta, Ravishankar Chandhiramoorthi, and Diego Didona.
 [SILK: Preventing Latency Spikes in Log-Structured Merge Key-Value Stores](https://www.usenix.org/conference/atc19/presentation/balmau). At *USENIX Annual Technical Conference*,
 July 2019.

1. Igor Canadi, Siying Dong, Mark Callaghan, et al.
 [RocksDB Tuning Guide](https://github.com/facebook/rocksdb/wiki/RocksDB-Tuning-Guide).
 *github.com*, 2023.
 Archived at [perma.cc/UNY4-MK6C](https://perma.cc/UNY4-MK6C)

1. Gabriel Haas and Viktor Leis.
 [What Modern NVMe Storage Can Do, and How to Exploit it: High-Performance I/O for High-Performance Storage Engines](https://www.vldb.org/pvldb/vol16/p2090-haas.pdf). *Proceedings of the
 VLDB Endowment*, volume 16, issue 9, pages 2090-2102.
 [doi:10.14778/3598581.3598584](https://doi.org/10.14778/3598581.3598584)

1. Emmanuel Goossaert.
 [Coding for SSDs](https://codecapsule.com/2014/02/12/coding-for-ssds-part-1-introduction-and-table-of-contents/). *codecapsule.com*, February 2014.

1. Jack Vanlightly.
 [Is sequential IO dead in the era of the NVMe drive?](https://jack-vanlightly.com/blog/2023/5/9/is-sequential-io-dead-in-the-era-of-the-nvme-drive) *jack-vanlightly.com*, May 2023.
 Archived at [perma.cc/7TMZ-TAPU](https://perma.cc/7TMZ-TAPU)

1. Alibaba Cloud Storage Team.
 [Storage System Design Analysis: Factors Affecting NVMe SSD Performance (2)](https://www.alibabacloud.com/blog/594376). *alibabacloud.com*, January 2019. Archived at
 [archive.org](https://web.archive.org/web/20230510065132/https://www.alibabacloud.com/blog/594376)

1. Xiao-Yu Hu and Robert Haas.
 [The Fundamental Limit of Flash Random Write Performance: Understanding, Analysis and Performance Modelling](https://dominoweb.draco.res.ibm.com/reports/rz3771.pdf).
 *dominoweb.draco.res.ibm.com*, March 2010.
 Archived at [perma.cc/8JUL-4ZDS](https://perma.cc/8JUL-4ZDS)

1. Lanyue Lu, Thanumalayan Sankaranarayana Pillai,
 Andrea C. Arpaci-Dusseau, and Remzi H. Arpaci-Dusseau.
 [WiscKey: Separating Keys from Values in SSD-conscious Storage](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf). At *4th USENIX Conference on File and
 Storage Technologies* (FAST), February 2016.

1. Peter Zaitsev.
 [Innodb Double Write](https://www.percona.com/blog/innodb-double-write/).
 *percona.com*, August 2006.
 Archived at [perma.cc/NT4S-DK7T](https://perma.cc/NT4S-DK7T)

1. Tomas Vondra.
 [On the Impact of Full-Page Writes](https://www.2ndquadrant.com/en/blog/on-the-impact-of-full-page-writes/). *2ndquadrant.com*, November 2016.
 Archived at [perma.cc/7N6B-CVL3](https://perma.cc/7N6B-CVL3)

1. Mark Callaghan.
 [Read, write & space amplification - B-Tree vs LSM](https://smalldatum.blogspot.com/2015/11/read-write-space-amplification-b-tree.html). *smalldatum.blogspot.com*, November 2015.
 Archived at [perma.cc/S487-WK5P](https://perma.cc/S487-WK5P)

1. Mark Callaghan.
 [Choosing Between Efficiency and Performance with RocksDB](https://codemesh.io/codemesh2016/mark-callaghan). At *Code Mesh*, November 2016.
 Video at [youtube.com/watch?v=tgzkgZVXKB4](https://www.youtube.com/watch?v=tgzkgZVXKB4)

1. Subhadeep Sarkar, Tarikul Islam
 Papon, Dimitris Staratzis, Zichen Zhu, and Manos Athanassoulis.
 [Enabling Timely and Persistent Deletion in LSM-Engines](https://subhadeep.net/assets/fulltext/Enabling_Timely_and_Persistent_Deletion_in_LSM-Engines.pdf). *ACM Transactions on Database Systems*,
 volume 48, issue 3, article no. 8, August 2023.
 [doi:10.1145/3599724](https://doi.org/10.1145/3599724)

1. Lukas Fittl.
   [Postgres   vs. SQL Server: B-Tree Index Differences & the Benefit of Deduplication](https://pganalyze.com/blog/postgresql-vs-sql-server-btree-index-deduplication).
   *pganalyze.com*, April 2025.
   Archived at [perma.cc/XY6T-LTPX](https://perma.cc/XY6T-LTPX)

1. Drew Silcock.
   [How Postgres stores data   on disk – this one's a page turner](https://drew.silcock.dev/blog/how-postgres-stores-data-on-disk/). *drew.silcock.dev*, August 2024.
   Archived at [perma.cc/8K7K-7VJ2](https://perma.cc/8K7K-7VJ2)

1. Joe Webb.
   [Using   Covering Indexes to Improve Query Performance](https://www.red-gate.com/simple-talk/databases/sql-server/learn/using-covering-indexes-to-improve-query-performance/). *simple-talk.com*, September 2008.
   Archived at [perma.cc/6MEZ-R5VR](https://perma.cc/6MEZ-R5VR)

1. Michael Stonebraker, Samuel Madden, Daniel J.
 Abadi, Stavros Harizopoulos, Nabil Hachem, and Pat Helland.
 [The End of an Architectural Era (It’s Time for a Complete Rewrite)](https://vldb.org/conf/2007/papers/industrial/p1150-stonebraker.pdf). At *33rd International Conference on
 Very Large Data Bases* (VLDB), September 2007.

1. [VoltDB Technical Overview White Paper](https://www.voltactivedata.com/wp-content/uploads/2017/03/hv-white-paper-voltdb-technical-overview.pdf). VoltDB, 2017.
 Archived at [perma.cc/B9SF-SK5G](https://perma.cc/B9SF-SK5G)

1. Stephen M. Rumble, Ankita Kejriwal, and John K. Ousterhout.
 [Log-Structured Memory for DRAM-Based Storage](https://www.usenix.org/system/files/conference/fast14/fast14-paper_rumble.pdf). At *12th USENIX Conference on File and Storage
 Technologies* (FAST), February 2014.

1. Stavros Harizopoulos, Daniel J. Abadi,
 Samuel Madden, and Michael Stonebraker.
 [OLTP Through the Looking Glass, and What We Found There](https://hstore.cs.brown.edu/papers/hstore-lookingglass.pdf). At *ACM International Conference on Management of Data*
 (SIGMOD), June 2008.
 [doi:10.1145/1376616.1376713](https://doi.org/10.1145/1376616.1376713)

1. Per-Åke Larson, Cipri Clinciu, Campbell Fraser,
 Eric N. Hanson, Mostafa Mokhtar, Michal Nowakiewicz, Vassilis Papadimos, Susan L. Price, Srikumar
 Rangarajan, Remus Rusanu, and Mayukh Saubhasik.
 [Enhancements to SQL Server Column Stores](https://web.archive.org/web/20131203001153id_/http://research.microsoft.com/pubs/193599/Apollo3%20-%20Sigmod%202013%20-%20final.pdf). At *ACM International Conference on Management of Data* (SIGMOD), June 2013.
 [doi:10.1145/2463676.2463708](https://doi.org/10.1145/2463676.2463708)

1. Franz Färber, Norman May, Wolfgang Lehner, Philipp Große,
 Ingo Müller, Hannes Rauhe, and Jonathan Dees.
 [The SAP HANA Database – An Architecture Overview](https://web.archive.org/web/20220208081111id_/http://sites.computer.org/debull/A12mar/hana.pdf).
 *IEEE Data Engineering Bulletin*, volume 35, issue 1, pages 28–33, March 2012.

1. Michael Stonebraker.
 [The Traditional RDBMS Wisdom Is (Almost Certainly) All Wrong](https://slideshot.epfl.ch/talks/166). Presentation at *EPFL*, May 2013.

1. Adam Prout, Szu-Po Wang, Joseph Victor, Zhou Sun, Yongzhu
 Li, Jack Chen, Evan Bergeron, Eric Hanson, Robert Walzer, Rodrigo Gomes, and Nikita Shamgunov.
 [Cloud-Native Transactions and Analytics in SingleStore](https://dl.acm.org/doi/pdf/10.1145/3514221.3526055). At *ACM International Conference on Management of Data* (SIGMOD), June 2022.
 [doi:10.1145/3514221.3526055](https://doi.org/10.1145/3514221.3526055)

1. Tino Tereshko and Jordan Tigani.
 [BigQuery under the hood](https://cloud.google.com/blog/products/bigquery/bigquery-under-the-hood). *cloud.google.com*, January 2016.
 Archived at [perma.cc/WP2Y-FUCF](https://perma.cc/WP2Y-FUCF)

1. Wes McKinney.
 [The Road to Composable Data Systems: Thoughts on the Last 15 Years and the Future](https://wesmckinney.com/blog/looking-back-15-years/). *wesmckinney.com*, September 2023.
 Archived at [perma.cc/6L2M-GTJX](https://perma.cc/6L2M-GTJX)

1. Michael Stonebraker, Daniel
 J. Abadi, Adam Batkin, Xuedong Chen, Mitch Cherniack, Miguel Ferreira, Edmond Lau, Amerson Lin, Sam
 Madden, Elizabeth O’Neil, Pat O’Neil, Alex Rasin, Nga Tran, and Stan Zdonik.
 [C-Store: A Column-oriented DBMS](https://www.vldb.org/archives/website/2005/program/paper/thu/p553-stonebraker.pdf). At *31st International Conference on Very Large Data Bases*
 (VLDB), pages 553–564, September 2005.

1. Julien Le Dem.
 [Dremel Made Simple with Parquet](https://blog.twitter.com/engineering/en_us/a/2013/dremel-made-simple-with-parquet.html). *blog.twitter.com*, September 2013.

1. Sergey Melnik, Andrey Gubarev, Jing Jing Long,
 Geoffrey Romer, Shiva Shivakumar, Matt Tolton, and Theo Vassilakis.
 [Dremel: Interactive Analysis of Web-Scale Datasets](https://vldb.org/pvldb/vol3/R29.pdf). At *36th International Conference on Very Large Data Bases* (VLDB), pages
 330–339, September 2010.
 [doi:10.14778/1920841.1920886](https://doi.org/10.14778/1920841.1920886)

1. Joe Kearney.
 [Understanding Record Shredding: storing nested data in columns](https://www.joekearney.co.uk/posts/understanding-record-shredding). *joekearney.co.uk*, December 2016.
 Archived at [perma.cc/ZD5N-AX5D](https://perma.cc/ZD5N-AX5D)

1. Jamie Brandon.
 [A shallow survey of OLAP and HTAP query engines](https://www.scattered-thoughts.net/writing/a-shallow-survey-of-olap-and-htap-query-engines). *scattered-thoughts.net*, September 2023.
 Archived at [perma.cc/L3KH-J4JF](https://perma.cc/L3KH-J4JF)

1. Benoit Dageville, Thierry Cruanes, Marcin
 Zukowski, Vadim Antonov, Artin Avanes, Jon Bock, Jonathan Claybaugh, Daniel Engovatov, Martin
 Hentschel, Jiansheng Huang, Allison W. Lee, Ashish Motivala, Abdul Q. Munir, Steven Pelley, Peter
 Povinec, Greg Rahn, Spyridon Triantafyllis, and Philipp Unterbrunner.
 [The Snowflake Elastic Data Warehouse](https://dl.acm.org/doi/pdf/10.1145/2882903.2903741).
 At *ACM International Conference on Management of Data* (SIGMOD), pages 215–226, June 2016.
 [doi:10.1145/2882903.2903741](https://doi.org/10.1145/2882903.2903741)

1. Mark Raasveldt and Hannes Mühleisen.
 [Data Management for Data Science Towards Embedded Analytics](https://duckdb.org/pdf/CIDR2020-raasveldt-muehleisen-duckdb.pdf). At *10th Conference on Innovative Data Systems
 Research* (CIDR), January 2020.

1. Jean-François Im, Kishore Gopalakrishna, Subbu
 Subramaniam, Mayank Shrivastava, Adwait Tumbde, Xiaotian Jiang, Jennifer Dai, Seunghyun Lee, Neha
 Pawar, Jialiang Li, and Ravi Aringunram.
 [Pinot: Realtime OLAP for 530 Million Users](https://cwiki.apache.org/confluence/download/attachments/103092375/Pinot.pdf). At *ACM International Conference on Management of
 Data* (SIGMOD), pages 583–594, May 2018.
 [doi:10.1145/3183713.3190661](https://doi.org/10.1145/3183713.3190661)

1. Fangjin Yang, Eric Tschetter, Xavier
 Léauté, Nelson Ray, Gian Merlino, and Deep Ganguli.
 [Druid: A Real-time Analytical Data Store](https://static.druid.io/docs/druid.pdf).
 At *ACM International Conference on Management of Data* (SIGMOD), June 2014.
 [doi:10.1145/2588555.2595631](https://doi.org/10.1145/2588555.2595631)

1. Chunwei Liu, Anna Pavlenko, Matteo Interlandi, and Brandon Haynes.
 [Deep Dive into Common Open Formats for Analytical DBMSs](https://www.vldb.org/pvldb/vol16/p3044-liu.pdf).
 *Proceedings of the VLDB Endowment*, volume 16, issue 11, pages 3044–3056, July 2023.
 [doi:10.14778/3611479.3611507](https://doi.org/10.14778/3611479.3611507)

1. Xinyu Zeng, Yulong Hui, Jiahong Shen, Andrew Pavlo, Wes
 McKinney, and Huanchen Zhang. [An Empirical Evaluation of Columnar Storage Formats](https://www.vldb.org/pvldb/vol17/p148-zeng.pdf). *Proceedings of the VLDB Endowment*, volume 17,
 issue 2, pages 148–161.
 [doi:10.14778/3626292.3626298](https://doi.org/10.14778/3626292.3626298)

1. Weston Pace.
 [Lance v2: A columnar container format for modern data](https://blog.lancedb.com/lance-v2/).
 *blog.lancedb.com*, April 2024.
 Archived at [perma.cc/ZK3Q-S9VJ](https://perma.cc/ZK3Q-S9VJ)

1. Yoav Helfman.
 [Nimble, A New Columnar File Format](https://www.youtube.com/watch?v=bISBNVtXZ6M).
 At *VeloxCon*, April 2024.

1. Wes McKinney.
 [Apache Arrow: High-Performance Columnar Data Framework](https://www.youtube.com/watch?v=YhF8YR0OEFk). At *CMU Database Group – Vaccination Database Tech Talks*, December 2021.

1. Wes McKinney.
 [Python for Data Analysis, 3rd Edition](https://learning.oreilly.com/library/view/python-for-data/9781098104023/). O'Reilly Media, August 2022. ISBN: 9781098104023

1. Paul Dix.
 [The Design of InfluxDB IOx: An In-Memory Columnar Database Written in Rust with Apache Arrow](https://www.youtube.com/watch?v=_zbwz-4RDXg). At *CMU Database Group – Vaccination
 Database Tech Talks*, May 2021.

1. Carlota Soto and Mike Freedman.
 [Building Columnar Compression for Large PostgreSQL Databases](https://www.timescale.com/blog/building-columnar-compression-in-a-row-oriented-database/). *timescale.com*, March 2024.
 Archived at [perma.cc/7KTF-V3EH](https://perma.cc/7KTF-V3EH)

1. Daniel Lemire, Gregory Ssi‐Yan‐Kai, and Owen Kaser.
 [Consistently faster and smaller compressed bitmaps with Roaring](https://arxiv.org/pdf/1603.06549).
 *Software: Practice and Experience*, volume 46, issue 11, pages 1547–1569, November 2016.
 [doi:10.1002/spe.2402](https://doi.org/10.1002/spe.2402)

1. Jaz Volpert.
 [An entire Social Network in 1.6GB (GraphD Part 2)](https://jazco.dev/2024/04/20/roaring-bitmaps/). *jazco.dev*, April 2024.
 Archived at [perma.cc/L27Z-QVMG](https://perma.cc/L27Z-QVMG)

1. Daniel J. Abadi, Peter Boncz, Stavros
 Harizopoulos, Stratos Idreos, and Samuel Madden.
 [The Design and Implementation of Modern Column-Oriented Database Systems](https://www.cs.umd.edu/~abadi/papers/abadi-column-stores.pdf). *Foundations and Trends in
 Databases*, volume 5, issue 3, pages 197–280, December 2013.
 [doi:10.1561/1900000024](https://doi.org/10.1561/1900000024)

1. Andrew Lamb, Matt Fuller, Ramakrishna Varadarajan,
 Nga Tran, Ben Vandiver, Lyric Doshi, and Chuck Bear.
 [The Vertica Analytic Database: C-Store 7 Years Later](https://vldb.org/pvldb/vol5/p1790_andrewlamb_vldb2012.pdf).
 *Proceedings of the VLDB Endowment*, volume 5, issue 12, pages 1790–1801, August 2012.
 [doi:10.14778/2367502.2367518](https://doi.org/10.14778/2367502.2367518)

1. Timo Kersten, Viktor Leis, Alfons Kemper, Thomas
 Neumann, Andrew Pavlo, and Peter Boncz.
 [Everything You Always Wanted to Know About Compiled and Vectorized Queries But Were Afraid to Ask](https://www.vldb.org/pvldb/vol11/p2209-kersten.pdf). *Proceedings of the VLDB
 Endowment*, volume 11, issue 13, pages 2209–2222, September 2018.
 [doi:10.14778/3275366.3284966](https://doi.org/10.14778/3275366.3284966)

1. Forrest Smith.
   [Memory Bandwidth Napkin   Math](https://www.forrestthewoods.com/blog/memory-bandwidth-napkin-math/). *forrestthewoods.com*, February 2020.
   Archived at [perma.cc/Y8U4-PS7N](https://perma.cc/Y8U4-PS7N)

1. Peter Boncz, Marcin Zukowski, and Niels Nes.
   [MonetDB/X100: Hyper-Pipelining Query Execution](https://www.cidrdb.org/cidr2005/papers/P19.pdf).
   At *2nd Biennial Conference on Innovative Data Systems Research* (CIDR), January 2005.

1. Jingren Zhou and Kenneth A. Ross.
   [Implementing Database Operations Using SIMD Instructions](https://www1.cs.columbia.edu/~kar/pubsk/simd.pdf).
   At *ACM International Conference on Management of Data* (SIGMOD), pages 145–156, June 2002.
   [doi:10.1145/564691.564709](https://doi.org/10.1145/564691.564709)

1. Kevin Bartley.
 [OLTP Queries: Transfer Expensive Workloads to Materialize](https://materialize.com/blog/oltp-queries/). *materialize.com*, August 2024.
 Archived at [perma.cc/4TYM-TYD8](https://perma.cc/4TYM-TYD8)

1. Jim Gray, Surajit Chaudhuri, Adam Bosworth, Andrew
 Layman, Don Reichart, Murali Venkatrao, Frank Pellow, and Hamid Pirahesh.
 [Data Cube: A Relational Aggregation Operator Generalizing Group-By, Cross-Tab, and Sub-Totals](https://arxiv.org/pdf/cs/0701155). *Data Mining and Knowledge
 Discovery*, volume 1, issue 1, pages 29–53, March 2007.
 [doi:10.1023/A:1009726021843](https://doi.org/10.1023/A:1009726021843)

1. Frank Ramsak, Volker Markl, Robert Fenk, Martin
 Zirkel, Klaus Elhardt, and Rudolf Bayer.
 [Integrating the UB-Tree into a Database System Kernel](https://www.vldb.org/conf/2000/P263.pdf).
 At *26th International Conference on Very Large Data Bases* (VLDB), September 2000.

1. Octavian Procopiuc, Pankaj K. Agarwal, Lars
 Arge, and Jeffrey Scott Vitter.
 [Bkd-Tree: A Dynamic Scalable kd-Tree](https://users.cs.duke.edu/~pankaj/publications/papers/bkd-sstd.pdf). At *8th International Symposium on Spatial and Temporal Databases*
 (SSTD), pages 46–65, July 2003.
 [doi:10.1007/978-3-540-45072-6_4](https://doi.org/10.1007/978-3-540-45072-6_4)

1. Joseph M. Hellerstein, Jeffrey F. Naughton, and Avi Pfeffer.
 [Generalized Search Trees for Database Systems](https://dsf.berkeley.edu/papers/vldb95-gist.pdf).
 At *21st International Conference on Very Large Data Bases* (VLDB), September 1995.

1. Isaac Brodsky.
 [H3: Uber’s Hexagonal Hierarchical Spatial Index](https://eng.uber.com/h3/).
 *eng.uber.com*, June 2018.
 Archived at [archive.org](https://web.archive.org/web/20240722003854/https://www.uber.com/blog/h3/)

1. Robert Escriva, Bernard Wong, and Emin Gün Sirer.
 [HyperDex: A Distributed, Searchable Key-Value Store](https://www.cs.princeton.edu/courses/archive/fall13/cos518/papers/hyperdex.pdf). At *ACM SIGCOMM Conference*, August 2012.
 [doi:10.1145/2377677.2377681](https://doi.org/10.1145/2377677.2377681)

1. Christopher D. Manning, Prabhakar Raghavan,
 and Hinrich Schütze.
 <a href="https://nlp.stanford.edu/IR-book/">*Introduction to Information Retrieval*</a>.
 Cambridge University Press, 2008. ISBN: 978-0-521-86571-5, available online at
 [nlp.stanford.edu/IR-book](https://nlp.stanford.edu/IR-book/)

1. Jianguo Wang, Chunbin Lin, Yannis Papakonstantinou,
 and Steven Swanson.
 [An Experimental Study of Bitmap Compression vs. Inverted List Compression](https://cseweb.ucsd.edu/~swanson/papers/SIGMOD2017-ListCompression.pdf). At *ACM International Conference
 on Management of Data* (SIGMOD), pages 993–1008, May 2017.
 [doi:10.1145/3035918.3064007](https://doi.org/10.1145/3035918.3064007)

1. Adrien Grand.
 [What is in a Lucene Index?](https://speakerdeck.com/elasticsearch/what-is-in-a-lucene-index) At *Lucene/Solr Revolution*, November 2013.
 Archived at [perma.cc/Z7QN-GBYY](https://perma.cc/Z7QN-GBYY)

1. Michael McCandless.
 [Visualizing Lucene's Segment Merges](https://blog.mikemccandless.com/2011/02/visualizing-lucenes-segment-merges.html). *blog.mikemccandless.com*, February 2011.
 Archived at [perma.cc/3ZV8-72W6](https://perma.cc/3ZV8-72W6)

1. Lukas Fittl.
 [Understanding Postgres GIN Indexes: The Good and the Bad](https://pganalyze.com/blog/gin-index). *pganalyze.com*, December 2021.
 Archived at [perma.cc/V3MW-26H6](https://perma.cc/V3MW-26H6)

1. Jimmy Angelakos.
 [The State of (Full) Text Search in PostgreSQL 12](https://www.youtube.com/watch?v=c8IrUHV70KQ). At *FOSDEM*, February 2020.
 Archived at [perma.cc/J6US-3WZS](https://perma.cc/J6US-3WZS)

1. Alexander Korotkov.
 [Index support for regular expression search](https://wiki.postgresql.org/images/6/6c/Index_support_for_regular_expression_search.pdf). At *PGConf.EU Prague*, October 2012.
 Archived at [perma.cc/5RFZ-ZKDQ](https://perma.cc/5RFZ-ZKDQ)

1. Michael McCandless.
 [Lucene's FuzzyQuery Is 100 Times Faster in 4.0](https://blog.mikemccandless.com/2011/03/lucenes-fuzzyquery-is-100-times-faster.html). *blog.mikemccandless.com*, March 2011.
 Archived at [perma.cc/E2WC-GHTW](https://perma.cc/E2WC-GHTW)

1. Steffen Heinz, Justin Zobel, and Hugh E. Williams.
 [Burst Tries: A Fast, Efficient Data Structure for String Keys](https://web.archive.org/web/20130903070248id_/http://ww2.cs.mu.oz.au:80/~jz/fulltext/acmtois02.pdf).
 *ACM Transactions on Information Systems*, volume 20, issue 2, pages 192–223, April 2002.
 [doi:10.1145/506309.506312](https://doi.org/10.1145/506309.506312)

1. Klaus U. Schulz and Stoyan Mihov.
 [Fast String Correction with Levenshtein Automata](https://dmice.ohsu.edu/bedricks/courses/cs655/pdf/readings/2002_Schulz.pdf). *International Journal on Document Analysis and
 Recognition*, volume 5, issue 1, pages 67–85, November 2002.
 [doi:10.1007/s10032-002-0082-8](https://doi.org/10.1007/s10032-002-0082-8)

1. Tomas Mikolov, Kai Chen, Greg Corrado, and Jeffrey Dean.
 [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781).
 At *International Conference on Learning Representations* (ICLR), May 2013.
 [doi:10.48550/arXiv.1301.3781](https://doi.org/10.48550/arXiv.1301.3781)

1. Jacob Devlin, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova.
 [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805).
 At *Conference of the North American Chapter of the Association for Computational
 Linguistics: Human Language Technologies*, volume 1, pages 4171–4186, June 2019.
 [doi:10.18653/v1/N19-1423](https://doi.org/10.18653/v1/N19-1423)

1. Alec Radford, Karthik Narasimhan, Tim Salimans, and Ilya Sutskever.
 [Improving Language Understanding by Generative Pre-Training](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf). *openai.com*, June 2018.
 Archived at [perma.cc/5N3C-DJ4C](https://perma.cc/5N3C-DJ4C)

1. Matthijs Douze, Maria Lomeli, and Lucas Hosseini.
 [Faiss indexes](https://github.com/facebookresearch/faiss/wiki/Faiss-indexes).
 *github.com*, August 2024.
 Archived at [perma.cc/2EWG-FPBS](https://perma.cc/2EWG-FPBS)

1. Varik Matevosyan.
 [Understanding pgvector's HNSW Index Storage in Postgres](https://lantern.dev/blog/pgvector-storage).
 *lantern.dev*, August 2024.
 Archived at [perma.cc/B2YB-JB59](https://perma.cc/B2YB-JB59)

1. Dmitry Baranchuk, Artem Babenko, and Yury Malkov.
 [Revisiting the Inverted Indices for Billion-Scale Approximate Nearest Neighbors](https://arxiv.org/pdf/1802.02422).
 At *European Conference on Computer Vision* (ECCV), pages 202–216, September 2018.
 [doi:10.1007/978-3-030-01258-8_13](https://doi.org/10.1007/978-3-030-01258-8_13)

1. Yury A. Malkov and Dmitry A. Yashunin.
 [Efficient and robust approximate nearest neighbor search using Hierarchical Navigable Small World graphs](https://arxiv.org/pdf/1603.09320).
 *IEEE Transactions on Pattern Analysis and Machine Intelligence*, volume 42, issue 4, pages 824–836, April 2020.
 [doi:10.1109/TPAMI.2018.2889473](https://doi.org/10.1109/TPAMI.2018.2889473)

