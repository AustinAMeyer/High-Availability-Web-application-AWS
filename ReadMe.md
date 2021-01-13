# High-Availability-Web-Application-AWS
This is a project I created for Udacity's Cloud DevOps Nanodegree. The purpose of this project is to create a fully functioning network in AWS using Cloudformation.

The requirments for the Nanodegree can be found on this [rubric](https://review.udacity.com/#!/rubrics/2556/view)

You need to build the Udagram Network stack first to have the Udagram Server stack work.

The command line used to create the stacks should look like below:

Network stack:
`create.sh UdagramServers Udagram-Network.yml Udagram-Network-Paramaters.json`

Server stack:
`create.sh UdagramServers Udagram-Servers.yml Udagram-Servers-Paramaters.json`

### Tools Used
* AWS Cloudformation
* LucidChart
* Shell

### Network Diagram

![picture alt](https://github.com/AustinAMeyer/High-Availability-Web-application-AWS/blob/master/Project%202%20Diagram.png "NetworkDiagram")
