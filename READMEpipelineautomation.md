# Jenkins
 CI/CD Pipeline Automation 

## Scope
This project covers a series of operational Jenkins tasks. Each step includes screenshots, the commands used, and an explanation of the task's purpose. The focus areas include Groovy scripting for Jenkinsfile creation, troubleshooting and modification, front-end install, authorization and access controls, freestyle project creation and troubleshooting, CI/CD pipeline creation and troubleshooting, and SCM file management.

## Environment
- Jenkins (CI/CD Pipeline Management/Automation)(Front-end GUI)
- GitTea (SCM/VCS)
- Groovy scripting (Jenkinsfile authorship)
- Operating System: Ubuntu 22.04.5 LTS
- Jenkinsfiles for free project and pipeline automation

## Tasks
### Install Jenkins on the host, validate install completed.
![Step1](images/step1.jpg)

### Install required JDK pre-requisite and confirmed running on the host.
![Step2](images/step2.jpg)

### Set Jenkins to start at host boot, confirm running on port 8085 from default port of 8080, start the daemon.
![Step3](images/step3.jpg)

### Confirm version of installed JDK, and that the Jenkins daemon is running with no issues.
![Step4](images/step4.jpg)

### Create initial test script, chmod permissions to 755, test script and confirm it is functional.
![Step5](images/step5.jpg)

### Obtain default admin password for initial login to GUI.
![Step6](images/step6.jpg)

### Confirm GUI resolves, login with initial admin token, create first user in engine.
![Step7](images/step7.jpg)

### Install plugins, review failures and errors, continue on as troubleshooting failures is outside of the scope of this project.
![Step8](images/step8.jpg)

### Create freestyle project, run the project, confirm completed without issue.
![Step9](images/step9.jpg)

### Execute first freestyle project, review script output, confirm returned as expected and no errors observed.
![Step10](images/step10.jpg)

### Validate first freestyle project build history and confirm matches expected output.
![Step11](images/step11.jpg)

### Build two freestyle projects, second one is a dependancy of the first project, validate first run both triggered the second and neither returned any issues.
![Step12](images/step12.jpg)

### Install the Copy Artifact plugin and validate completed without issue.
![Step13](images/step13.jpg)

### Run both freestyle projects after plugin installation asnd confirm both complete without issue.
![Step14](images/step14.jpg)

### Set the system message as well as the number of executors. 
![Step15](images/step15.jpg)

### Define number of the executors on the host.
![Step16](images/step16.jpg)

### Create multi-step pipelin3, install the Copy Artifact plugin, configure the build parameters, modify the build steps, run the job, confirm the artifact was copied and that all jobs completed without error.
![Step17](images/step17.jpg)

### Validate secondary job ran after confirming the first job in the pipeline completed succesfully.
![Step18](images/step18.jpg)

### Create pipeline, launch run, confirm run completes without error.
![Step19](images/step19.jpg)

### Create pipeline, troubleshoot issue(s) with Jenkinsfile, push to GitTea, run job again, confirm completes without issue.
![Step20](images/step20.jpg)

### Generate new API token for next pipeline run via curl.
![Step21](images/step21.jpg)

### Kick off pipeline with sleep timer defined via REST API.
![Step22](images/step22.jpg)
