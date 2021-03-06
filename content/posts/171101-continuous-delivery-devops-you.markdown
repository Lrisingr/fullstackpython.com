title: DevOps, Continuous Delivery... and You
slug: devops-continuous-delivery-you
meta: Talk slides, notes and more resources for a technical talk on basic DevOps and continuous delivery concepts, by Matt Makai.
category: post
date: 2017-11-01
modified: 2017-11-01
headerimage: /img/visuals/talk-header.jpg
headeralt: Comment bubble with code representing a technical talk-based blog post.


This blog post contains the slides along with a loose transcript and 
additional resources from my technical talk on DevOps and Continuous
Delivery concepts given at my alma mater, the University of Virginia,
to the [M.S. in Management of Information Technology program](https://www.commerce.virginia.edu/ms-mit) on November 2nd and 4th of 2017.
Links to learn more about the concepts presented in this talk can
be found at the bottom of the page.

----


<img src="/img/171101-devops-cd-you/devops-cd-you.001.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Title slide for technical talk.">

Hey folks, my name is Matt Makai. I'm a 
[software developer at Twilio](https://www.twilio.com/blog/2014/02/introducing-developer-evangelist-matt-makai.html)
and the creator of [Full Stack Python](https://www.fullstackpython.com/),
where over 125,000 developers read each month to learn how to 
[build](/web-development.html), [deploy](/deployment.html) and 
[operate](/devops.html) Python-based applications.


<img src="/img/171101-devops-cd-you/devops-cd-you.004.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="What's the point of Agile?">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.005.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Docker logo.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.006.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Cargo ship with containers.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.007.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Kubernetes logo.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.008.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Agile sprints need to ship code into production to create anything of value.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.009.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Move fast and break things.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.010.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="If you do not have the right processes and tools in place eventually production will break.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.011.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Fight the urge to put manual processes in place that slow you down. You must automate.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.012.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Some teams try to get around the production problem by shipping to dev, but they still are not creating value.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.013.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="This session is about DevOps and Continuous Delivery.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.014.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="What DevOps is NOT.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.015.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="What DevOps IS.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.016.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="What Continuous Delivery is.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.017.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Move fast and BUILD things.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.018.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="San Francisco skyline at night.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.019.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Twilio billboard, ask your developer!">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.020.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="August 2013.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.021.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="How customers pay for Twilio.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.022.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Hacker News post on Twilio not billing correctly.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.023.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Billing incident update blog post.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.024.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Redis logo.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.025.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads 'Root cause?'">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.026.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Billing incident response from Twilio developer evangelist.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.027.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Twilio status page.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.028.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Twilio number of production deployments.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.029.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads 'tools and concepts'.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.030.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Eventually you ship code into production that breaks your application.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.031.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads 'automated testing' with example code coverage in the background.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.032.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Automated tests in dev only deploy to production when they are successful.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.033.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Bugs can still occur in production.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.034.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads 'monitoring and alerting' with New Relic dashboard in the background.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.035.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="When something breaks in prod, your developers know about it and can fix the problem.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.036.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="When production is running smoothly with many tests, do that increase the chance of black swan-type events?">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.037.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads 'Chaos engineering' with the chaos engineering monkey logo in the background.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.038.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Chaos engineering introduces intentional failures in your infrastructure both on a scheduled and unschedule basis.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.039.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads '1. other peoples money' with money in the background.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.040.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads '2. other peoples lives' with people in the background.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.041.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads 'War on Terror' with an exploded vehicle in the background.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.042.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="U.S. military and civilian casualties in Iraq.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.043.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Biometrics devices.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.044.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Eclipse IDE.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.045.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="The situation did not have reasonable deployments to dev or to production.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.046.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Start somewhere, automate your deployments to dev environment.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.047.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Some environments have tricky issues with automated prod deployments like disconnected networks.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.048.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads 'Tools and concepts'.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.049.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Several development teams commit to a Git repository.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.050.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads 'continuous integration' with a screenshot of Jenkins dashboard in the background.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.051.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Add a continuous integration server to build the code that is committed to your source control repository.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.052.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="How do we automate the building of these environments and the deployments themselves?">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.053.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Text that reads 'configuration management' with a screenshot of Ansible AWX in the background.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.054.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Agile sprints deliver code to a development environment and then automate the deployment into production.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.055.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Review list of continuous delivery tools.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.056.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="A list of more concepts and tools for continuous delivery.">

...


<img src="/img/171101-devops-cd-you/devops-cd-you.057.jpg" width="100%" class="technical-diagram img-rounded" style="border: 1px solid #aaa" alt="Thank you slide.">

That's all for today. My name is [Matt Makai](/about-author.html)
and I'm a software developer at [Twilio](/twilio.html) and the
author of [Full Stack Python](https://www.fullstackpython.com/),
thank you very much.


----

Additional resources to learn more about the following topics can be found
on their respective pages:

* [Deployments](/deployments.html)
* [Continuous integration](/continuous-integration.html)
* [Serverless computing](/serverless.html)
* [AWS Lambda](/aws-lambda.html)
* [Static site generators](/static-site-generator.html)
* [Monitoring](/monitoring.html)
* [DevOps](/devops.html)
* [Configuration management](/configuration-management.html)
* [Platform-as-a-Service (PaaS)](/platform-as-a-service.html)
* [Docker](/docker.html)
* [Web application security](/web-application-security.html)
* [Testing](/testing.html)
* [Source control](/source-control.html)
* [Git](/git.html)
* [Hosted source control services](/hosted-source-control-services.html)
* [GitHub](/github.html)
* [Code metrics](/code-metrics.html)
* [NoSQL](/no-sql-datastore.html)
