# My Static Website using AWS Amplify

This is a static website containing HTML, CSS, and JavaScript.  
It can be deployed on AWS Amplify, S3, CloudFront, or any static hosting platform.

## Features
- Easy to deploy on AWS
- AWS Amplify already includes a built-in CDN, so setting up CloudFront separately is not required
- Easy Git-based deployments with automatic builds
- Built-in CI/CD for frontend apps

## Pre-requisites
Keep the repo ready with required files like HTML, CSS and JS

## Deployment Steps
1. Set Up a New AWS Amplify App
	Go to AWS Amplify Console → https://console.aws.amazon.com/amplify/

	Click "Deploy App" → Select "Create new app"

	Choose "Git-based deployment" (as used in this case)
	
2. Connect Your Git Repository

	Authorize AWS Amplify to access your repository.

	Select the repository containing your static website files. In this case sri-static-web

	Install & Authorize

4. Deploy the

 	Add repository and branch from the dropdowns

 	Click 'Next' using default settings -> Save & Deploy

	![image](https://github.com/user-attachments/assets/612da3da-2f88-4228-ab1b-ee7e5943a89a)


Note : Amplify.yml file used for build configuration is optional. If the project is a simple static site (HTML, CSS, JS only), Amplify automatically detects and deploys your files without needing a build configuration.
