# Deploy a static Website with using Cloudfront





<h2>Description</h2>

This project consist in deploying a static website with the target being a html file stored in a S3 bucket. Upon deploying we will be using Aws service Cloudfront to help cache our content. This will allow us to lower latency to better favorize customer experience. Meaning fast access to our application / content.


<br />
<br />
<br />



<h2>Services Used </h2>

- <b>AWS Route 53</b>

- <b>AWS S3</b> 

- <b>AWS Cloudfront</b>

- <b>AWS Certificate Manager</b>


<br />



<h2>Program walk-through:</h2>

<p align="center">

 <br />

- <b>First create the bucket that is gonna host our application content.

 [Refer to the step in the repository about creating a static website with S3](https://github.com/Liioou/Deploy-a-static-Website-with-S3.git)
 <br/>
<br />
<br />



- <b> On route 53 purchase the domain name of the website you are trying to create 
<br />
<br />


- <b> < Or if already have a registered domaine make sure subdomain match the bucket name you are using to create the static website >
<br />
<br />




- <b> Next create a record and select Alias. choose "Alias to S3 website endpoint" and select the region associated to the bucket:

<img src="https://i.imgur.com/PHVWWr6.png" height="80%" width="80%" alt="Create static website steps"/>
<br />
<br />


- <b> Test it:



<img src="https://i.imgur.com/GGs7oET.png" height="80%" width="80%" alt="Create static website steps"/>
<br />
<br />



- <b> Create image of the instance and test it





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
