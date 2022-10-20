This is a sample web application to demonstrate the build, security scan and deploy stage. Following are the steps to reproduce.

1. Written the web app code in Visual studio.
2. Pushed the project in the Github repository.
3. Created a workflow script in Github actions to automate the process and created the CiCd pipeline, which includes the build, security scan and deploy stages one after the other.
4. Pushed the image to Docker hub repo.
5. Used AWS EKS service to deploy the build if all the above stages have been successfull.  