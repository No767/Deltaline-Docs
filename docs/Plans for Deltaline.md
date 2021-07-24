# Plans for Deltaline

As I'm building the backend Django framework, I have noticed that Netlify (current hosting company) doesn't support Django Frameworks and only static sites (basically ones made from HTML + CSS, and JS, React, Vue.js, etc). So, the next plan is to self host this on Docker. Below this is a list of things that need to be planned out in order to host this and run it properly.

- Switch from Netlify to Docker + Nginx based system
- Use CI/CD system (the Jenkins CI that was already in place for another project) to deploy and automatically update the servers as needed
- Nginx Web server with MySQL support
- Possibly use Nginx as a reverse proxy?


## Other Plans

Deltaline isn't just a side project for me, it's more or less a way to optimize things and to bring a fast and smooth experience. There are more plans later on that I have. 

- Rewrite backend to use Django 3.2.5 LTS instead
- Complete rewrite to use the Django backend framework

