# Basics of Docker and Conrainers 

<ul>
<li>Terraform code will create EC2 and ECR in AWS Cloud 9 enviroment </li>
<li>The configured GitHub Action performs the automatic build of container images and push the images to Amazon ECR</li>
</ul>



# Requirements
<table><th> Name</th> <th> Version </th>
  <tr><td>aws</td><td>>= 3.72r</td></tr>
  <tr><td>terraform</td><td>>= 0.13.1</td></tr>
  </table>
  
# Providers
<table><th> Name</th> <th> Version </th>
  <tr><td>aws</td><td>>= 3.72r</td></tr>
   </table>
   
   
# User Inputs

 Create Secret Keys in Github from AWS Details page


<table><th> Name</th> 
  <tr><td> AWS_ACCESS_KEY_ID</td></tr>
    <tr><td> AWS_SECRET_ACCESS_KEY</td></tr>
    <tr><td> AWS_SESSION_TOKEN</td></tr>
   </table>
  
 # Commands to run docker and containers
 
<ul>
<li>aws ecr get-login --region us-east-1 </li>
<li>docker pull aws_account_id.dkr.ecr.us-west-2.amazonaws.com/amazonlinux:latest</li>
  <li>docker run -d -p 8080:80 aws_account_id.dkr.ecr.us-west-2.amazonaws.com/amazonlinux:latest</li>
    <li>docker images</li>
      <li>docker ps</li>
</ul>

 # Author
 

Sneha Pillay

 
# Acknowledgement
 
<b>Prof. Irina Geiman for her kind guidance and timely help  &#128512;</b>



