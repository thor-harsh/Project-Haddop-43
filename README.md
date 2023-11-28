# Project-Haddop-43-Challenges-




# Project--Hadoop-42-Challenges-

<table>
  
**In this project We will use Spark with Python to do an amazing stuff.Here we will work on the Spark DataFrame which will read the csv files attached above as our dataset and complete the challenges as provided by Jose Portilla .** <br></br>

**Here is the Problem Statement!** <br></br>

A large technology firm needs your help, they've been hacked! Luckily their forensic engineers have grabbed valuable data about the hacks, including information like session time,locations, wpm typing speed, etc. The forensic engineer relates to you what she has been able to figure out so far, she has been able to grab meta data of each session that the hackers used to connect to their servers. <br></br> These are the features of the data:<br></br>


'Session_Connection_Time': How long the session lasted in minutes <br></br>
'Bytes Transferred': Number of MB transferred during session <br></br>
'Kali_Trace_Used': Indicates if the hacker was using Kali Linux <br></br>
'Servers_Corrupted': Number of server corrupted during the attack <br></br>
'Pages_Corrupted': Number of pages illegally accessed <br></br>
'Location': Location attack came from (Probably useless because the hackers used VPNs) <br></br>
'WPM_Typing_Speed': Their estimated typing speed based on session logs. <br></br>

The technology firm has 3 potential hackers that perpetrated the attack. Their certain of the first two hackers but they aren't very sure if the third hacker was involved or not. They have requested your help! Can you help figure out whether or not the third suspect had anything to do with the attacks, or was it just two hackers? It's probably not possible to know for sure, but maybe what you've just learned about Clustering can help!<br></br>

**One last key fact**, the forensic engineer knows that the hackers trade off attacks. Meaning they should each have roughly the same amount of attacks.<br></br> For example if there were 100 total attacks, then in a 2 hacker situation each should have about 50 hacks, in a three hacker situation each would have about 33 hacks. The engineer believes this is the key element to solving this, but doesn't know how to distinguish this unlabeled data into groups of hackers.<br></br>


**Before jumping to the code lets understand Spark and Clustering First**...<br></br>

**What is Apache Spark?** <br></br>

Apache Spark™ is a multi-language engine for executing data engineering, data science, and machine learning on single-node machines or clusters.<br></br>
Unify the processing of your data in batches and real-time streaming, using your preferred language: Python, SQL, Scala, Java or R.
Execute fast, distributed ANSI SQL queries for dashboarding and ad-hoc reporting. Runs faster than most data warehouses.<br></br>
Perform Exploratory Data Analysis (EDA) on petabyte-scale data without having to resort to downsampling.
Train machine learning algorithms on a laptop and use the same code to scale to fault-tolerant clusters of thousands of machines.<br></br>

**What is Spark DataFrames**?<br></br>

**1**: Spark 2.0 shifted towards DataFrame syntax<br></br>
**2**: are now the standard way of using Spark's ML Capabilties<br></br>
**3**: Spark Docs are still new<br></br>
**4**: DataFrame is very familiar to Pandas DataFrames<br></br>
**5**: Columns = features<br></br>
**6**: Rows = records<br></br>

**What is Clustering**?<br></br>
Clustering or cluster analysis is a machine learning technique, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points. The objects with the possible similarities remain in a group that has less or no similarities with another group."<br></br>

It does it by finding some similar patterns in the unlabelled dataset such as shape, size, color, behavior, etc., and divides them as per the presence and absence of those similar patterns.It is an unsupervised learning method, hence no supervision is provided to the algorithm, and it deals with the unlabeled dataset.<br></br>

K-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean, serving as a prototype of the cluster.<br></br>


**Important Note: Go through the hack_data.csv file before jumping to the code.**


</table>

**So what are you waiting for...? Jump to the code to get started. As usual for any doubt or query see you in pull request section 😁😂. Thanks!**


