1. This code is for Arithmetic and Array operations in Java and contains JUnit test cases for the same.
2. This Repo configure to AWS code-build and run the build by using lambda function whenever a new commit on this repo master branch.
3. if build success then lambda send the build status to developer mail id using SNS topic.
4. If build success then it stores in S3 bucket and triggers the new lambda for copy that builds into EC2 and set the CLASSPATH for the build.
