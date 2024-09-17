java c
CP3402 Supplementary Assignment
Task:
In this individual assignment, you will develop and deploy one WordPress site. Your site must be designed using a child theme that you create based on an existing theme. You must use and document an appropriate modern development and deployment workflow for this project that includes version control as well as both local and production environments.
Note: This assignment is similar to, but different from, the main CP3402 project. In that project, you worked in a team and made many of your own decisions for choice of technologies and systems. In this assignment, you work individually and some of the choices are prescribed for you (e.g., local development environment, automation using GitHub, etc.). You will develop a child theme (not a full theme from a starter) and you only need local and production, not staging, environments. Please read these requirements carefully.
Design:
You should perform. all the usual design steps like information architecture, interface design and information design. All design decisions are up to you except for anything specified as a requirement by the client. Your theme design should be appropriate for your goal and target audience.
Your child theme must make significant noticeable changes to the parent theme.
Content:
Content is provided by the client. You should modify and improve any provided content as appropriate for the site goals. It is likely that there will be small sections of your site that would benefit from new content  that you can reasonably write by yourself, but you are not expected to create much new content or do substantial editing. While you may use extra content including images not provided by the client, you must comply with any legal requirements for commercial use. Your final site content should be suitable for the goals, target audience, and client. Some of the client content could be considered "out of date", but you should make the site using the provided information.
Documentation:
You must produce an industry-style. README.md in your project repository that clearly covers two sections to allow a new developer to continue developing (WordPress theme details) and deploying (publishing workflow) your site. This is non-trivial, and the documentation must be written so that someone could  follow it successfully. Note that you do not need to describe basic steps that are clearly covered in WordPress documentation. Use effective Markdown for high-quality document presentation including  headings, links, code blocks, lists, etc. Your documentation must look professional and be well-written.
•   Theme Development - Describe the changes your child theme contributes and how/where further changes to the child theme should be made
•    Deployment - This should explain the process of making changes to the site including local, testing and deployment to production - both in terms of how it is setup and how someone should make new changes.
Use the "dogfooding" approach and write your documentation so that a new developer could follow the steps and details in your documentation. We will test this by following your instructions explicitly.
Report:
Include an additional markdown file in your repository, REPORT.md. This is like the LinkedIn report from the main CP3402 project. In this report, summarise this project, highlighting the technologies and tools used and the skills you developed. The intended aud代 写CP3402 Supplementary AssignmentSQL
代做程序编程语言ience for this is a prospective employer, so emphasise your own employability.
Requirements and Resources:
You must appropriately use a project management board as part of your own development workflow. You can use either Trello or GitHub Projects as your project management board. Ensure your board is public.
Version Control
You must use 'proper' version control for your child theme code. Commit locally using git with best-practice messages. Push your commits to GitHub. Do not 'upload' directly to GitHub or modify your code or documentation using GitHub's website editor. Use your own GitHub account/repository for this. It should  be kept up-to-date throughout the project. You only need to put the parent theme, your child theme, and your documentation under git. Do not include core WordPress files.
Local Development Environment
You must use an industry-style. Linux-based local development environment using either:
•   Vagrant, or
•    Docker
You will have either a Vagrantfile or a docker-compose.yml file for your local. Include this in your repo.
It is not acceptable to use environments like WAMP, XAMP, Flywheel, etc. Provide a reasonable description of your local environment in the deployment section of your README and REPORT.
Deployment Hosting
Your production site must be published on a public web server using one of the following (each of which have free/student tiers available):
•   Amazon Web Services (AWS)
•    DigitalOcean
•    Microsoft Azure
•   Google Cloud
Deployment Workflow
You must setup and use a publishing workflow using an automated process that takes changes to your repo (theme code) and publishes these to your production site. This can be done using webhooks, GitHub Actions or some other suitable automation method. Your process must not be manual, but based on commits to the repo. This needs to be documented, as explained above. You do not need to automate the process of migrating the site and database between local and production, only the theme code.
You must add your marker as a collaborator with push access to your GitHub repository. During marking, this person will follow your documentation step-by-step to change your child theme then commit and push to your repository. Your automation must then publish this change to production, and your site must show the updated theme.
Integrity:
The work you submit for this assignment must be your own. You are allowed to discuss the assignment with other students and get assistance from your peers, but you may not do any part of anyone else’swork for them and you may not get anyone else to do any part of your work. Work that is too similar to another’s work or work from an outside source will be dealt with promptly according to University procedures for handling plagiarism. For this assignment, it is acceptable to appropriately use permitted resources and modify to suit your project, but you should cite the original source in your documentation HTML file.
Submission:
A template submission file, supplementary.html, is provided for you. Complete this with the requested information, including login details and links to your site and repository, and upload it to LearnJCU.You also need to submit separate zip files of your parent theme and child theme, and a WordPress export of your site. Please do these as separate files - do not zip them all up into one.



         
加QQ：99515681  WX：codinghelp
