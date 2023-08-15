Downloaded the zip file from the link that was sent and unzipped it
Created a New repository : Deployment-1 and uploaded the the files from earlie
Created a documentation.md file to document the process
Logged into the instructor Jenkins Server
Clicked on New -> selected pipeline then pipeline from SCM
In SCM-> clicked Git and copy pasted my repository (Deployment-1) URL
Clicked Credential -> Add Jenkins -> added my github Username as the Username and for Password I need to generate my token
GENERATING TOKEN
- Went into my github -> Developer's settings -> Personal access token -> Tokens(classics) -> Generate new token (Classic)
- Logged in to get access
- Note: First Deployment-> clicked Repo and Generate token
- Copied the new token
Pasted the token in the password for the credential
ID- FirstDeployment-Saraswati
Description-> First Deployment
Add
Credential- My username
Branch Specification-  from */master to */main
Click Apply and Save
Click Build Now and its shows its completed successfully



