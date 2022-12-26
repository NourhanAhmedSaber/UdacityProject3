## Project3: Give Application Auto-Deploy Superpowers

In this project, will prove the mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

The CI/CD benefits proposal contains essential benefits of CI/CD, and describes the business context that will benefit from the automation tools. Explanation should include benefits that translate to revenue and cost for the business.

Section 1: Selling CI/CD to your Team/Organization  Done and submitted.

Section 2: Deploying Working, Trustworthy Software  Done and submitted.

- A public git repository with your project code. [URL01]
- Evidence of code-based CI/CD configuration in the form of yaml files in your git repository.
- Console output of various pre-deploy job failure scenarios:
- Build Jobs that failed because of compile errors. [SCREENSHOT01]
- Failed unit tests. [SCREENSHOT02]
- Failure because of vulnerable packages. [SCREENSHOT03]
- An alert from one of your failed builds. [SCREENSHOT04]
- Compile errors have been fixed.
- Unit tests have been fixed.
- All critical security vulnerabilities caught by the “Analyze” job have been fixed.
- Console output of appropriate failure for infrastructure creation job (using CloudFormation). [SCREENSHOT05]
- Console output of a smoke test job that is failing appropriately. [SCREENSHOT06]
- Console output of a successful rollback after a failed smoke test. [SCREENSHOT07]
- Console output of successful promotion of new version to production in CloudFront. [SCREENSHOT08]
- Console output of successful cleanup job that removes old S3 bucket and EC2 instance. [SCREENSHOT09]
- Evidence that the deploy jobs only happen on the master branch. [SCREENSHOT10]
- Evidence of deployed and functioning front-end application in an S3 bucket [URL02].
- Evidence of deployed and functioning front-end application in CloudFront. [URL03_SCREENSHOT]
- Evidence of healthy back-end application. [URL04_SCREENSHOT]


Section 3: Turn Errors into Sirens
I am currently working on this section with using the Prometheus server, and will submit it once done and completed successfully to be reviewd.





