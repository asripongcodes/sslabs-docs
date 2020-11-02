# Introduction </ins>

## Getting Started

SCB Developer Platform empowers developers to deploy code with zero downtime, through automating DevOps with its in-built infrastructure configurations and test frameworks. This documentation provides a quick overview of the platform, its features, and currently available code templates.

SCB Developer Platform offers two types of code templates for digital project deployments: API (Node.JS, Java, Python languages available) and Web (React and Angular languages available). 

When signed up, you become a BETA user. In the near future, we will open up a NON-BETA version.

As a BETA user of a pre-release version of the SCB Developer Platform, please feel free to contact the SS Labs team with your issues or feedback.

| Person   | Email|
| :-------: | ------- |
| Tor (Developer Lead)  | [samphan.pojanasophanakul@scb.co.th](mailto:samphan.pojanasophanakul@scb.co.th) |
| Pun (Developer Lead) | [attaphon.ongvisit@scb.co.th](mailto:attaphon.ongvisit@scb.co.th) |
| Krieng (Business Lead) | [kriengkri.pongpanjanthra@scb.co.th](mailto:kriengkri.pongpanjanthra@scb.co.th) |


**Step 1: Signing Up**

Follow the instructions below to get started on SCB Developer Platform.

1. Visit [SS Labs Site](https://www.sslabs.sh/)

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/landing+page.jpg)

2. Click on “Get Started with GitHub” 
3. Sign into your GitHub account. Enter your GitHub log in information: username or email address and password, to sign in. If you do not have a GitHub account, click on “Create an account” link to create one.

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/Sign+in+with+GitHub.png)

4. Once signed in through GitHub, you will see the following landing page.

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/accept+email.png)

5. Check the email address associated with your GitHub account for an invitation from SS Labs to join SS Labs’ GitHub Repository.

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/Sign+in+with+GitHub-1.png)

6. Return to the same invitation page on the SS Labs website. Click on “Begin Your Journey!” button

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/accept+email.png)

7. Set up your team by inputting your Team Name and Description (optional). Only English and the special character “-” can be used in "Team Name" and "Team description" fields. 

	Please note that team members can only be added to each team manually for now. Please contact SSLabs / Innovation Lab team with your team member’s email to add a member to your team. 

	When done, click the “Let’s code” button.
	
	![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/team+setup.png)

8. Please see Step 2.1: Creating Your First Project Template or Step 2.2: Creating Your First Code Repository for the next screen.

---------------

### For Those Using SCB Developer Platform to deploy digital projects:

**Step 2.1: Creating Your First Project Template**

1. Click on either the “Create Project” button at the top right corner, or, for users without any projects, the “Create your first project to start coding” link under the Project Dashboard header.

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard.png)

2. From the pop up on Project Dashboard screen, select “Create Project Template” choice (LEFT).

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard_+create+project+template.png)

3. Select from tabs below whether to create an API or Web project

### API Template Tab:

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/create+project.png)

### Web Template Tab:

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/create+project-1.png)

4. Fill in: 
	* Project name
	* Project description (optional). 
	* Note that “Owner” field is already pre-populated with your teamname and that only English and the special character “-” can be used. 
	* Click “Back to Project,” if you wish to return to the Project Dashboard page. (This will cancel the creation of a new project.)

5. When done, click on the “Let’s code” button.
6. A Provisioning page appears. SCB Developer platform is preparing the following for your project:
	*  A Code Repository on GitHub
	*  CI/CD Pipelines
	*  An Image Repository
	*  A Microservice Deployment

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/project+provisioning.png)

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/project+provisioning-1.png)

Once provisioning is completed, each box's circle will display a tickmark.

7. The Project Dashboard page displays

	* Project Count: The current number of projects
	* status (provisioning or running)
	* type (API or Web app)
	*  a button to "View Project" which takes you to an individual project's "Project Detail" page

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard_+project+list.png)


8. Each project's Project Detail page displays the following:

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/project+detail_+project+template.png)

* Base URL of the project's endpoint 
* Current Deployment version (clicking on the link to the right of the text refreshes to display the latest deployment version as a link and in the Deploy History)
* Application Log (redirects to DataDog)
* "Go to GitHub" (redirects to the project's GitHub code repository)
* Clone (click to view and copy the project's GitHub URL)
* Deployment History from the master branch (status can be In Progress, Success)

A sample application log in DataDog looks like this:

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/ReactDataDogLog.png)

A sample project's GitHub page looks like this:

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/ProjNodeJSGitHub.png)

---------------



### For Those Using SCB Developer Platform to Host GitHub Repository

**Step 2.2: Creating Your First Code Repository**

1. Click on either the “Create Project” button at the top right corner, or, for users without any projects, the “Create your first project to start coding” link under the Project Dashboard header.

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard.png)

2. From the pop up on Project Dashboard screen, select “Create code repository” choice (RIGHT).

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard_+create+blank+project.png)

3. Fill in Project name, Project description (optional). 

	* Note that “Owner” field is already pre-populated with your teamname and that only English and the special character “-” can be used. Click “Back to Project,” if you wish to return to the Project Dashboard page. (This will cancel the creation of a new project.)

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/create+blank+project.png)

4. When done, click on the “Let’s code” button. 

5. You will be redirected back to the Project Dashboard page. Notice that the Blank project row on the Project Dashboard page displays a “Completed” instead of “Running” status, and redirects to “GitHub” (code repository) instead of to the Web or API project.

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/Project_Dashboard_Repo.jpg)

6. Click on “View Project” (rightmost button) to view GitHub History. Notice that the project detail does not display “Base URL” or “Current Deployment”. There is no “Application Log” button to the right of the “GitHub History” header.

7. The code repository's Project Detail page displays the code repository's GitHub History. 

	* Click on "Go to GitHub" to visit the project's code repository on GitHub
	* Clone (click to view and copy the project's GitHub URL)
	* Click on the links to follow GitHub's instructions for getting started.

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/project+first+detail+blank+project.png)

**Step 3: Check Current Platform Limitations**

See also: Release Notes

Currently SCB Developer Platform allows you to create the projects in the following languages:

1. API Projects
	* Node.JS
	* Java
	* Python

2. Web Projects
	* React
	* Angular