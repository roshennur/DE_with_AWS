<h1 align="center">Triggering an AWS Lambda function when a new file arrives in an S3 bucket.</h1>
<p>We're going to configure an S3 bucket to automatically trigger a lambda function whenever a new file is written to the bucket.</p>
<h2>First we'll create a Lambda Layer that allows Lambda function to bring in additional code. In this example we will use  AWS SDK for Pandas Python Library.</h2>
<h3>To create Lambda Layer download awswrangler version 3.16.1 for python version 3.14 from https://github.com/aws/aws-sdk-pandas/releases </h3>
<p align="left">
  <img src="screenshots/1.png" width="1000" height="600"/>
</p>
