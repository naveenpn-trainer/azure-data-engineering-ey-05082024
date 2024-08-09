# Getting Started with Big Data and Frameworks

>Big Data refers to the data which is **large, fast and complex type** of structured, semi-structured and unstructured data generated from a variety of different sources, which becomes difficult to store and process using a **traditional processing system (RDBMS)**

**Challenges of Big Data**

1. Storage : Distributed Storage System
2. Processing : MPP (Massive Parallel Processing)

## Distributed Systems

>  A DS is a collection of autonomous system that are physically separated but are linked together

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd2kcAMy5XhHQ0VF2SK79OmNVLLtOcnhp9Ot3Ve3Uwl7jDZz0H8MttSrL27RyQengtz4eSNRFt0CpkdRE8HC5DK9Fqbvk8sU_587VmgkvR8BC0tdU3sKAlU2ncUeNQkr3S1L0LsJjqCpBouC7UtnDKhevY?key=ZDQI9yPkLwmZ3ZH_j9fetA)

## Hadoop

> Apache Hadoop is a software framework that allows us to **store and process large datasets** **in parallel and distributed system.**

## Components of Hadoop

Hadoop consists of 3 main components

1. Storage Layer : **HDFS  (Hadoop Distributed FS)**
2. Resource Management Layer : YARN (**Yet Another Resource Negotiator**)
3. Data Processing Layer : **MapReduce**

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXc3jyVhRCwQ8yPL8-dB4SqZnqfudm0V-xn5qo3I5g7MLfQ_vD9XK-qoABNXiVP_7CHAUP7G_mtoI_BOlmjz8KnmO9xqQRekQrNB_V4H5bdB-7tvDLlANDt-FPwH-RqQjGAT5enDLxFXKkLlpYrM4a1Mvs6B?key=KG4XycolQz2vWFq2bNIfEQ)

* Hadoop MapReduce is **deprecated**.

## Hadoop Daemon Services

1. NameNode
2. SecondaryNameNode
3. DataNode
4. ResourceManager
5. NodeManager

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfxSNs-u9H3wbI8VJ4l2dwBuHIPKfK7um25yNXG7PDI7t0I8N8gyNJCdYOhlrbzdLTUMHwU3QltJXz-AU3h9Iu5SaeRvHOrqw6pyWYSVvUqDJC_72MGNY8dcBf6rO7ehwXeLklzY6ttLVJ60veL96OA9l4Z?key=KG4XycolQz2vWFq2bNIfEQ)

## Master and Slave Architecture

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcYvz7qbKxkJ1J9y2_83shURZhPY_Ugj4PS4Ot0iueubUlxenEawbrpQdyJQTGbbH4nimpPLv1nlZS4ayrfvMST3cyf_OGDTFRlDSzVhWWTYdnR9WZbWipOAUuw2kRVhXSKS1FG7JFzW91acPLok5ULMctY?key=KG4XycolQz2vWFq2bNIfEQ)

## HDFS and Architecture

> HDFS is a **distributed** and **scalable** file system designed for storing very large files.

**Distributed**

* The files are stored across multiple machines, HDFS splits the file into smaller pieces (Blocks), distributes these blocks into multiple machines.

  ![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXflMq034gdBekabLMAA0w-qKqRegK9FFKsMn4TIVHhIoP-0fDWeCL066YDqokF0_4QwW6cGmNHSfvLWfaVY5CyD3ekpeztWbUTmO_wcfvQ-XKfED30-HaoxHLhpMorI89Fv9U19CK5RxQCP0R5yXg5Uc5gi?key=KG4XycolQz2vWFq2bNIfEQ)

* The block size in 128 MB (configurable)

* 300 MB --> 128 MB   128 MB 44 MB.

* To handle fault tolerance , Hadoop replicates each block thrice



## Big Data / Hadoop Ecosystem

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXczLTkrPA4tvyeM973XHovRFzuP28wgKb4PNO3z_lfR1NM967eB58zaDpcsVxAb7v_m-0LFS1PjziQxI0TltKVpnoXVXL56DxH5266rgOd_woEmL3yJ01XQJ9IsJwaZhpIQpPwMSmRHy3wTZAuahvkmL-wx?key=KG4XycolQz2vWFq2bNIfEQ)



## Map Reduce

> MR is a programming paradigm to process the data in parallel in multiple machines.

* MR comes with lot of IO operations



## YARN

> Yet Another Resource Negotiator

YARN consists of 3 main components

1. Resource Manager
2. Node Manager
3. Application Master



**Important Points**

* When you work with Hadoop, provides two Web UI
  * NameNode UI : Browse HDFS
  * Resource Manager UI : Track the job exeuction



































