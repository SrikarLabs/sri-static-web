# My Static Website using AWS Amplify

This is a static website containing HTML, CSS, and JavaScript.  
It can be deployed on AWS Amplify, S3, CloudFront, or any static hosting platform.

## 📌 Features
- Responsive design
- Simple JavaScript interaction
- Easy to deploy on AWS

## 🚀 Deployment Steps
1. Set Up a New AWS Amplify App
	Go to AWS Amplify Console → https://console.aws.amazon.com/amplify/

	Click "Deploy App" → Select "Create new app"

	Choose "Git-based deployment" (as used in this case)
	
2. Connect Your Git Repository

	Authorize AWS Amplify to access your repository.

	Select the repository containing your static website files. In this case sri-static-web

	Install & Authorize
	
Note : Amplify.yml file used for build configuration is optional. If the project is a simple static site (HTML, CSS, JS only), Amplify automatically detects and deploys your files without needing a build configuration.
