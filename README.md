# Summary
### Setting up Simple Notification Services (SNS) with AWS using Boto 3. 

<p>
This project uses the Simple Notification Service (SNS) of AWS. Several basic functions like creating topics, subscriptions, publishing are explained. The functionality is extended with a newly created helper package by me. This is a work in progress. 
</p>

<p> 
It relies heavily on the  
<a href = https://boto3.amazonaws.com/v1/documentation/api/latest/index.html target=_blank> 
Boto3 documentation.</a> <br> 
According to the doc: 
</p> 

<p> 
“You use the AWS SDK for Python (Boto3) to create, configure, and manage AWS services, such as Amazon Elastic Compute Cloud (Amazon EC2) and Amazon Simple Storage Service (Amazon S3). The SDK provides an object-oriented API as well as low-level access to AWS services.” 
</p> 

<p>This project creates an  

### S3_helpers_pckg 

<p> 
The package stores a class with useful helper functions, mostly manipulating the dicts of responses.<br> 
The functions are mostly self defined, but other functions for example from Github and the doc are integrated.<br> 
In this case credits are given.<br> 
The pckg is a work in progress. <br>
Functions defined here are added later to the helper package.

</p> 

<p>Several topics are examined here. <br> 
For example:</p> 
<ul> 
<li>Setting up AWS for SNS.</li> 
<li>Creating clients.</li> 
<li>Creating topics.</li> 
<li>Subscriptions.</li> 
<li>Unsuscribe.</li> 
<li>Endpoints.</li> 
<li>Publishing messages.</li>     
</ul> 


<p> 
The credentials are secured with a <a href="www.dotenv.org/docs" target=_blank> 
dotenv.</a>
</p> 
 