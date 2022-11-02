# Module 20 Individual Self Assessment

## Pipeline and AWS Systems Scope of Work Overview 

### My scope of the work in the Team II project was to create a pipeline that would List, Read, and Write to an AWS S3. Another part of the SoW was to create a pipeline from the AWS S3 to the AWS RDS Postgres Server, using AWS GLUE, and make that available to the team. Overall, the project was completed with the exception of the S3 to RDS because it was not feasible because each team member would need to connect to the S3. The solution would have been access to my RDS directly but ultimately that was not needed. 

 

## Pipeline 

### A pipeline was necessary to take the API called and cleansed data and push it to a common data repository for the team to access. This step was not necessary, but it was done as a technology demonstration as part of the coursework. 

### Originally the course work was done in Pyspark and I used modified code to make the connection, however; it was realized later that this code would not work in Jupyter Notebook which is what was decided to be used. The code was then rewritten in Jupyter Notebook using Python with Boto3, StringIo, and pandas. 

## AWS 

### The AWS infrastructure in the project was not necessary but we wanted to use it as part of the technology demonstration. I created a pipeline from the S3 to the notebook and then from the S3 to an AWS RDS Postgres Database using AWS Glue. This was inconvenient for the team to use individual GLUE setups and it was not thought of to use the endpoint to directly to my Postgres server. 

## Conclusion 

### Overall, there were many things to learn about the AWS infrastructure, and while many of our plans did not work out, these were great opportunities to learn the ins-and-outs of Amazon Web Service and how they could be brough to bear in a work environment without the need to spin up local hardware resources. 
