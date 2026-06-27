<h1 align="center">With AWS DMS replicating a database into an Amazon S3 based data lake.</h1>
<h2>1.Deploying MySQL and an EC2 data loader via CloudFormation</h2>
<h3>To get started download the CloudFormation template from mysql-ec2loader.cfn and save it.</h3>
<h3>In AWS Management Consoles search bar, search for CloudFormation -> Create stack</h3>
<p align="left">
  <img src="screenshots/1.png" width="1000" height="600"/>
</p>
<h3>Specify template section -> Upload template file -> Select file mysql-ec2loader.cfn you downloaded -> Next</h3>
<p align="left">
  <img src="screenshots/2.png" width="1000" height="600"/>
</p>
<h3>For Stack name, provide a name you like</h3>
<p align="left">
  <img src="screenshots/3.png" width="1000" height="600"/>
</p>
<h3>leave the rest of the parameters as default and Submit</h3>
<p align="left">
  <img src="screenshots/4.png" width="1000" height="600"/>
</p>
<h3>once the deployment finished, the stack status will change to CREATE_COMPLETE</h3>
<p align="left">
  <img src="screenshots/5.png" width="1000" height="600"/>
</p>
