<h1> Working with EBS (AWS) </h1>


<h2>Description</h2>
In this lab I focused on Amazon Elastic Block Store (Amazon EBS), which is a key storage mechanism for Amazon EC2 instances. The lab involved creating and managing EBS volumes, attaching them to EC2 instances, and performing various tasks to understand their functionality. Specifically, I created a new EBS volume, attached and mounted it to an EC2 instance, formatted the volume with a file system, created a snapshot of the volume, and restored the snapshot to a new volume. This process demonstrated the durability, reliability, and ease of use of Amazon EBS volumes for persistent storage in the cloud.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Amazon Web Services (AWS) Management Console</b>
- <b>AWS EC2</b>
- <b>Amazon EBS</b>
- <b>PuTTY (for SSH connection)</b>
- <b>Linux Command-Line Tools</b>

<h2>Program Screenshots:</h2>

<p align="center">
Volume tag information: <br/>
<img src="https://i.imgur.com/CZ2pSwA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Volume and Instance information:  <br/>
<img src="https://i.imgur.com/foe2FzB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure PuTTY to not timeout: <br/>
<img src="https://i.imgur.com/TNWke3X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Linux terminal authentication screen :  <br/>
<img src="https://i.imgur.com/fk6f6gx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Added new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point:  <br/>
<img src="https://i.imgur.com/eklQPV6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
EBS Snapshot tag information : <br/>
<img src="https://i.imgur.com/hYDTQE8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Recreated EBS volume tag information : <br/>
<img src="https://i.imgur.com/A8POIF2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Restored Volume and Instance information : <br/>
<img src="https://i.imgur.com/RfyHdi8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Mount the Restored Volume :  <br/>
<img src="https://i.imgur.com/N3PvEUx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
