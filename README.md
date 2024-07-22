# Andrew Walser's Cloud-Based Resume

### The purpose of this project is to create a central location of not only my skills, education, and employment history, but to also display a real life example of my coding, infrastructure, and automation knowledge.

This project was created using multiple technologies and processes. Below is a full description of each step that was taken to set up and maintain the project.

The live hosted version of this project can be viewed on: https://a-walser.com

## ** Amazon Web Services **
- IAM - Following security best practices, this project is managed through multiple roles configured with IAM using MFA.

- Budgeting - This project uses a zero-dollar budgeting limit with automated notifications if the limit is passed

- AWS S3 - File hosting

- AWS Cloudfront - CDN for static content & https configuration

- AWS Route 53 - DNS Service & Domain name registration

- AWS Certificate Manager: Valid certificate for the domain (a-walser.com) and subdomain (www.)

## ** Web Development **
- HTML / CSS - Basic website information and design

## ** Version Control **
- git - Manage local repo

- Github - Store and display public repo

- ssh - Cloning & pushing commits

** CI/CD **
- Github Actions - Deploys all updated files from 'Websites/' to AWS S3 when a push occurs on the main branch
