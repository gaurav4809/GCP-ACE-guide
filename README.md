# GCP-ACE-guide
This repository is for ACE prep
Google Cloud Certification : Associate Cloud Engineer
Image result for associate cloud engineer logo
Associate Cloud Engineer Badge
Introduction
We are going to see details about Google Cloud Associate Engineer certification. This one is more operational than the other two exams (Data Engineer & Cloud Architect). This will have a mix of conceptual and hands-on scenario based questions.

You will find simple considerations drawn from my experience about the exam and ways to prepare for the exam in efficient and faster way. A few trick and tips for both prep and taking on this exam.

This is a little tricky exam I wouldn’t say it is difficult but as it just touches the surface of all topics in GCP so it gets a little overwhelming on how much to cover and how much to leave for preparation that being said its achievable with some hands on practice and some command line memorization.

Don’t appear for this exam unless you have some level of comfort using gcloud commands.

You can find the topics, details and practice test for this certification here.

Exam Type
This is a multiple choice objective exam with all of the question being single answer . This exam covers a range of topics from all of Google cloud but in a limited manner. A bit from each one of the topics; compute, data, Networking, deployment & security.

To pass this exam you should have a hands on experience with Google cloud command line utility (gcloud ) and good to have familiarity with Kubernetes command line (kubectl).

This is more of operational exam and evaluates your knowledge of setting up a actual GCP project, designing, developing and managing solutions on Google Cloud.

50 multiple choice questions in 2 hrs, trust me you will have enough time to complete the exam and even revisit all marked answers couple of times.

What all to Study and from where ?
I would recommend you to study following the Google Cloud documentation and the reason I say that is because its always updated, follows the sequence in which the topics are needed to be understood or related. Go through how-to along with the concepts but not in deeper details.Practice the gcloud commands in parallel.


Each Google Product documentation will have these Sections
You can also follow Courses available on Udemy or Coursera to build basic understanding but make sure to spend sometime on documentation during the preparation.

Listing below the topics that needs to be covered for this exam.

Main Topics :

This exam will have very limited scope for Data Engineering questions and relies heavily on compute and network services of Google Cloud.

Compute ( This will cover around 40–50 % questions)

Compute Engine — Instance, Instance Groups ( Managed, Unmanaged), Image, Snapshots etc.
App Engine — App Engine Flex, Traffic splitting, Rollback etc.
Google Kubernetes Engine — Autoscaling, container resize, service communication etc. ( at least 7–8 questions, I know surprising)
Cloud Functions
Networking (20–30%)

VPC/Shared VPC (at least couple of questions)
Firewall Rules — Ingress/Egress traffic, allow, deny etc.
Load Balancing — Internal , External, HTTP, TCP/IP etc.(Definitely few questions)
CIDR Addressing (Definitely few questions)
VPN— Interconnect, Cloud VPN etc.
Google Command Line Utility ( 15–20% questions)

gcloud commands — gsutil, pubsub, container, instance etc. Use the link for ready reference, don’t try all commands just the basic ones. Like creating instance from command line, command to increase size of kubernetes clusters etc.
Data (Very few and very basic)

Cloud Storage — Bucket Type, Transfer Service, LCM etc.
Cloud SQL/Spanner — Failover, Horizontal scaling etc.
Big Query — Data Sharing etc
Supporting Topics (few questions on this):

Stackdriver — Monitoring, Logging, trace etc. (Couple of questions)
IAM — Google Groups, roles, recommend practices for access, service accounts
Service Costing, Pricing Calculator — Make sure to play around with it to understand all about pricing
As soon as you get the basic hold of these topics study with practice questions so as to get yourself acquainted with type of questions that may appear in exam.

At the start you will not be able to answer everything so don’t worry get back to documentation or to the Building Blocks (Compiled Notes).
Depending on your style of learning make sure to prepare short notes this will help before the exam day.

The Trick
As mentioned earlier in the post this exam is little tricky few questions can have all unrelated options and can be little confusing as well. Follow this trick below :

For conceptual questions - Remember keywords/terminologies associated with a particular tool/technology in GCP, this helps decode answers quickly. For Eg. Dedicated Interconnect — High Speed Connectivity, No network hops etc. Kubernetes — Micro services, Container orchestration etc.
For hands-on questions — Well am afraid their are no tricks you need to know the commands !!
How Much Time ?
Very usual question, however it varies as per individuals learning style. As this certification exam just scratches the surface of services with Google cloud don’t go much deeper into concepts, spent sufficient amount of time practicing gcloud commands.

Conclusion
So, keep it simple, concise and don’t try to read from too may sources. Go ahead prepare well and give it a shot and get a chance to earn a free official Google merchandise too (if certification is not enough to motivate :P ) !!!

This certification exam can be a good practice if you are also planning to take up Professional Architect certification exam which is a level deeper but covers almost same set of topics along with few additional topics.

Happy Learning & All the Best !!

