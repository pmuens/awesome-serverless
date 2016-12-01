# Awesome Serverless [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/justserverless/awesome-serverless/master/logo_serverless.png" align="right" width="100">](http://serverless.com)

> A curated list of resources regarding the [Serverless framework](https://serverless.com) (formerly JAWS) and the serverless architecture.

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list project.*

**Say *hello* on [Twitter](https://twitter.com/pmmuens).**

## Table of contents

- [General](#general)
- [Blogs](#blogs)
- [Blog posts](#blog-posts)
- [Screencasts](#screencasts)
- [Talks](#talks)
- [Amazon AWS resources](#amazon-aws-resources)
- [Projects / Services](#projects--services)
- [Related projects](#related-projects)
- [Plugins](#plugins)
- [Literature](#literature)
- [Professional services](#professional-services)
- [Deprecated](#deprecated)
  - [General](#general)
  - [Projects (v0.5)](#projects-v05)
  - [Plugins (v0.5)](#plugins-v05)
  - [Modules](#modules)
  - [Literature](#literature)

---

## General

- [Homepage](http://serverless.com) - Official homepage.
- [Documentation](http://docs.serverless.com) - Documentation.
- [GitHub organization](http://github.com/serverless) - Official GitHub organization.
- [Twitter](https://twitter.com/goserverless) - Official Twitter account.
- [Forum](http://forum.serverless.com) - Official Serverless forum.
- [Meetups](http://serverlessmeetups.com) - List with all official Serverless meetups.
- [Vimeo](https://vimeo.com/user2421131) - JAWS Vimeo account.
- [YouTube](https://www.youtube.com/channel/UCFYG383lawh9Hrs_DEKTtdg) - Serverless YouTube account.
- [Roadmap](https://github.com/serverless/serverless/milestones) - GitHub milestones.
- [Stack Overflow](http://stackoverflow.com/questions/tagged/serverless-framework) - Stack Overflow questions.
- [Gitter Chat](https://gitter.im/serverless/serverless) - Chat with the community.
- [Serverless cost calculator](http://serverlesscalc.com) - Calculate your costs for different providers.
- [ServerlessConf](http://serverlessconf.io) - Serverless specialized conference.
- [Serverless Camp](https://serverless.camp) - Code camps to learn more about serverless.
- [Serverless Heroes Resources](https://github.com/ServerlessHeroes/serverless-resources) - Another great list with serverless related resources.

## Blogs

- [Just Serverless](http://justserverless.com/blog) - Blog about the Serverless framework.
- [Serverless Code](https://serverlesscode.com) - Blog about everything serverless related.
- [Serverless Zone](https://serverless.zone) - Everything Serverless related.
- [Serverless Blog](http://blog.serverless.com) - Official blog of the Serverless Framework.
- [Serverless Stories](https://medium.com/serverless-stories) - Medium publication from the team behind the Serverless Framework.

## Blog posts

- [Infoword article](http://www.infoworld.com/article/2990795/cloud-computing/jaws-takes-a-bite-out-of-aws-lambda-app-deployment.html) - Infoworld blog post discussing Serverless (formerly known as JAWS).
- [Interview with the Parallax agency](https://serverlesscode.com/post/david-guetta-online-recording-with-lambda) - Interview how [This ones for you](http://thisonesforyou.com) was developed with the Serverless framework.
- [Example AWS infrastructure](https://serverlesscode.com/images/guetta_article/image04.png) - Example cloud infrastructure for a Serverless project.
- [Build a Serverless REST API in Minutes with the Serverless Framework](https://blog.codeship.com/a-serverless-rest-api-in-minutes/) - Most recent "getting started" post as of Jan 2016.
- [Moving from Ruby on Rails to Serverless](http://microapps.com/blog/learnt-building-monolithic-rails-app/) - Blog post why and how this transition was made.
- [Zerosharp blog posts series](http://blog.zerosharp.com/serverless-framework-part-1-up-and-running/) - Step-by-step development of an example application.
- [Serverless and GraphQL](http://kevinold.com/2016/02/01/serverless-graphql.html) - How Serverless can be used with GraphQL.
- [Serverless - The next big thing](https://www.linkedin.com/pulse/serverless-next-big-thing-colin-lyman) - Colin Lyman on Serverless as the next big thing.
- [Building a website](http://zanon.io/posts/building-serverless-websites-on-aws-tutorial) - Tutorial on how to build a serverless website.
- [Add CORS support](http://davidcai.github.io/blog/posts/serverless-and-cors/) - How you can add CORS support to your Serverless functions.
- [AWS lambda framework "Serverless"](http://thenewstack.io/serverless-offers-framework-aws-lambda/) - Article about the Serverless framework.
- [Using Python](https://serverlesscode.com/post/python-on-serverless-intro/) - Using Python with Serverless.
- [Scheduled Lambda events](http://jamiecressey.com/2016/02/27/everyone-to-the-cloud/) - How to create scheduled Lambda events.
- [Trek10 about Serverless](https://www.trek10.com/blog/serverless-framework-for-processes-projects-and-scale/) - A look at Serverless for processes, projects and scale.
- [Serverless Slackbots](http://eng.localytics.com/serverless-slackbots-powered-by-aws/) - Slackbot implementation with Serverless.
- [5 serverless computing frameworks to watch out for](http://www.forbes.com/sites/janakirammsv/2016/03/22/five-serverless-computing-frameworks-to-watch-out-for/#7a810ffc59d7) - Forbes blog post which compares five serverless frameworks.
- [Caching for API Gateway](http://theburningmonk.com/2016/04/serverless-enable-caching-on-query-string-parameters-in-api-gateway) - Enable caching on query string parameters.
- [The Serverless revolution](http://davidwells.io/the-serverless-revolution/) - Blog post which gives a great introduction to the serverless architecture.
- [What happens when you collaborate with valve](https://www.reddit.com/r/webdev/comments/3oiilb/our_company_did_a_collab_with_valve_for_some_new/) - Great writeup which shows how Serverless helped a startup to handle massive traffic.
- [Architecting a Serverless web application](https://blog.fugue.co/2016-05-05-architecting-a-serverless-web-application-in-aws.html) - Insightful read on how to architecture a serverless web application.
- [How to avoid integration platform teething](http://www.base2services.com/community/articles/2016/05/03/how-to-avoid-integration-platform-teething-problems.html#.VzR1TWPjYcs) - Nice article why Serverless matters.
- [Express to AWS Lambda](https://medium.com/@johncmckim/express-to-aws-lambda-part-1-a057096abe34#.ecn3bqaso) - Blog post series which compares Express to AWS Lambda / Serverless.
- [Cloudcademy blog post about Serverless](http://cloudacademy.com/blog/serverless-framework-aws-lambda-api-gateway-python/) - Deep overview of Serverless.
- [Serverless computing use cases](http://thenewstack.io/serverless-computing-use-cases-image-processing-social-cognition/) - Blog post about the ServerlessConf and Serverless use cases.
- [A match made in heaven](http://blog.gorillastack.com/serverless-framework-lambda-a-match-made-in-heaven/) - Blog post by GorillaStack which shows the power of Serverless environment variables.
- [Serverless computing growing quickly](http://thenewstack.io/serverless-computing-growing-quickly/) - Overview why Serverless computing is taking over traditional application development.
- [MongoDB with Serverless](http://blog.east5th.co/2016/06/06/mongodb-with-serverless/) - How you can use MongoDB with Serverless.
- [ServerlessConf recap](http://cloudacademy.com/blog/serverlessconf-recap-serverless/) - Recap about the first ServerlessConf.
- [Volume compute for a new generation](http://redmonk.com/fryan/2016/04/28/serverless-volume-compute-for-a-new-generation/) - Brief overview what the serverless architecture is and why it matters.
- [Serverless secrets](https://www.trek10.com/blog/serverless-secrets) - Blog post on the "serverless secrets" plugin and how to share secrets in a Serverless project in general.
- [Martin Fowler blog post](http://martinfowler.com/articles/serverless.html) - Martin Fowler blog post on Serverless architectures.
- [Continuous Deployments with Serverless](https://hackernoon.com/continuous-deployments-with-serverless-v0-5-c29138d6debf#.3v6qnw9qv) - How to do continuous deployments with Serverless.
- [Building Serverless framework v1](http://blog.serverless.com/building-serverless-framework-v1/) - Blog post announcing v1.0.
- [Serverless HipChat connect](https://developer.atlassian.com/blog/2016/06/gorillastack-serverless-hipchat-connect/) - Walkthrough of Serverless HipChat connect.
- [Scout Alarms move to Serverless](http://blog.scoutalarm.com/post/146675810396/scout-platform-update-behind-the-scenes) - Short blog post why Scout Alarm decided to use Serverless.
- [Serverless v1.0 alpha1 announcement](http://blog.serverless.com/serverless-v1-0-alpha1-announcement/) - Serverless announcement blog post about v1.0 alpha 1.
- [Migrating from v0 to v1](https://serverless.zone/migrating-from-serverless-v0-5-to-v1-0-part-one-setup-config-and-deployment-9c926c8c56f9#.1kko041kx) - Blog post series about the migration process from v0 to v1.
- [The life of a Serverless Microservice](https://cloudonaut.io/the-life-of-a-serverless-microservice-on-aws/) - Interesting read on how to build a production ready Serverless application (everything described there could also be done with the Serverless framework).
- [Serverless buddies](https://serverless.zone/serverless-buddies-npm-packages-that-will-make-your-life-easier-e70cef1a08d1#.t5xih9dyl) - Blog post about npm packages which will help during Serverless development.
- [Npm registry server with Serverless](https://medium.com/@mgrenier/experiment-npm-registry-server-with-serverless-30992341507a#.9xj2625gz) - Blog post about the npm registry which was built with the help of the Serverless framework.
- [Serverless v1.0 alpha2 announcement](http://blog.serverless.com/serverless-v1-0-alpha-release-2/) - Serverless announcement blog post about v1.0 alpha 2.
- [Economics may drive serverless](http://highscalability.com/blog/2016/7/27/economics-may-drive-serverless.html) - "Controversial" blog post about the serverless movement.
- [Why the future of software and apps is serverless](http://readwrite.com/2012/10/15/why-the-future-of-software-and-apps-is-serverless/) - Old blog post (2012) by Iron.io about the upcoming Serverless movement.
- [What is serverless computing and why is it important](https://www.iron.io/what-is-serverless-computing/) - Iron.io blog post about Serverless.
- [Serverless v1.0 beta1 announcement](http://blog.serverless.com/serverless-v1-0-beta-release-1/) - Serverless announcement blog post about v1.0 beta 1.
- [AWS Lambda in a VPC with Serverless](https://serverless.zone/aws-lambda-in-a-vpc-with-the-serverless-framework-7c3b92c151ad#.rro8p8f25) - Blog post which shows how one can setup AWS Lambda and VPC with the help of the Serverless framework.
- [Making sense of serverless computing](http://thenewstack.io/making-sense-serverless-computing/) - Blog post which goes into details about possible implementation scenarios / pros- and cons about Serverless computing.
- [The serverless cloud](https://jaxlondon.com/the-serverless-cloud-part-1/) - Blog post series about serverless computing in general.
- [Building a RESTful API](https://cloudonaut.io/create-a-serverless-restful-api-with-the-serverless-framework-powered-by-api-gateway-lambda-and-dynamodb/) - Tutorial on how to build a RESTful API with Serverless v1.0 beta 1.
- [Interview about Serverless v1](https://forrestbrazeal.com/2016/08/15/lambda-calculus-talking-serverless-with-florian-motlik/) - Interview with Florian from the Serverless team about the mission of the Serverless framework.
- [CI/CD with Serverless](https://serverless.zone/ci-cd-with-serverless-v1-0-0-beta-ccb332944c6#.3cmhb06zk) - Interesting read on how to use CI/CD systems with Serverless v1.
- [451 research report](https://451research.com/report-short?entityId=89566) - Overview of the Serverless status quo / analysis of existing FaaS providers.
- [30k page views for $0.21](https://fmlnerd.com/2016/08/16/30k-page-views-for-0-21-a-serverless-story/) - Success story about a web app which used the serverless architecture.
- [What does Serverless mean?](http://thenewstack.io/context-serverless-mean/) - Blog post which explains the context of the serverless architecture.
- [Serverless v1.0 beta2 announcement](http://blog.serverless.com/serverless-v1-0-beta-release-2/) - Serverless announcement blog post about v1.0 beta 2.
- [What is Serverless?](https://www.trek10.com/blog/what-is-serverless/) - Trek10 blog post which explains what Serverless is.
- [Scheduled Tasks](https://parall.ax/blog/view/3202/tutorial-serverless-scheduled-tasks) - Blog post by Parall.ax on how to setup scheduled tasks with Serverless.
- [Garden Aid](https://serverless.zone/serverless-architectures-9e23af71097a#.vk7w2p3ng) - John McKim describes how he built his Serverless IoT project "Garden Aid".
- [Game-changer or a recycled fad?](https://gojko.net/2016/08/27/serverless.html) - Critical post whether the serverless movement is just a hype or "The next big thing".
- [Azure functions vs. AWS Lambda](http://searchcloudcomputing.techtarget.com/tip/Serverless-showdown-Microsoft-Azure-Functions-vs-AWS-Lambda) - Comparison of Azure functions and AWS Lambda.
- [Serverless and Machine Learning](https://blog.alexcasalboni.com/serverless-computing-machine-learning-baf52b89e1b0#.y6nu7bgfc) - Post about serverless and machine learning.
- [AWS Lambda and SQS](http://theburningmonk.com/2016/04/aws-lambda-use-recursive-function-to-process-sqs-messages-part-1/) - Blog post series on how to use AWS Lambda with SQS.
- [Serverless is the new multitenancy](https://techcrunch.com/2016/09/01/serverless-is-the-new-multitenancy/) - Overview post which explains the serverless architecture.
- [Using DynamoDB with Serverless](http://blog.rowanudell.com/using-dyanmodb-with-serverless/) - Post which explains how to use Serverless v1 and DynamoDB.
- [Securing serverless applications](https://medium.com/@marknca/4-steps-to-secure-serverless-applications-1274f0f5d321#.rnkblbm65) - 4 Steps to secure serverless applications.
- [GraphQL with Serverless](https://serverless.zone/graphql-with-the-serverless-framework-79924829a8ca#.ev7vln9l7) - GraphQL with the Serverless Framework v1.
- [API around Google Cloud Vision](http://ramhiser.com/2016/09/05/serverless-api-around-google-cloud-vision-with-the-serverless-framework/) - Building a Serverless API around Google Cloud Vision.
- [Serverless v1.0 rc1 announcement](http://blog.serverless.com/new-release-serverless-v1-0-rc-1/) - Serverless announcement blog post about v1.0 release candidate 1.
- [Yemeksepetis shift to run serverless](https://aws.amazon.com/de/blogs/aws/yemeksepeti-our-shift-to-serverless-architecture/) - Blog post by the team behind Yemeksepeti about their shift to a serverless architecture.
- [Slack webhooks with Serverless](https://serverless.zone/slack-webhooks-with-the-serverless-framework-4c01bb3c1411#.iyub4e1b1) - Post which describes how to use Slack webhooks with the Serverless framework.
- [Serverless computing with Azure functions](http://www.hanselman.com/blog/WhatIsServerlessComputingExploringAzureFunctions.aspx) - Introduction to serverless computing with the help of Azure functions.
- [Autodesks sample serverless architecture](https://www.infoq.com/news/2016/08/serverless-autodesk) - A Sample Serverless Microservice Architecture from Autodesk.
- [Understanding the serverless trend](http://www.techrepublic.com/article/aws-vs-microsoft-azure-understanding-the-serverless-application-trend) - Blog post which outlines what the serverless trend is all about.
- [Architecture code patterns](http://blog.serverless.com/serverless-architecture-code-patterns/) - Different serverless arhcitectural code patterns explained.
- [Serverless without the framework](https://serverlesscode.com/post/serverless-without-the-framework/) - Blog post which explains why you should learn the fundamentals before using the framework.
- [Local Serverless development](http://blog.gorillastack.com/serverless-framework-local-development-environments) - Tutorial how you can develop offline with Serverless (v0.5).
- [Serverless and JAM](https://www.netlify.com/blog/2016/09/15/serverless-jam---a-serverless-framework-tutorial/) - Tutorial on how to use Serverless with the JAMstack.
- [Serverless "Hello World"](https://foobar123.com/serverless-hello-world-b8fa41279537#.dulikehjp) - Quick intro to the serverless technology and the Serverless Framework.
- [How to build a serverless Node.js microservice](https://medium.freecodecamp.com/building-a-nodejs-microservice-on-aws-lambda-6adb6da53cbb#.esr503ot0) - Step-by-step guide on how to create a CRUD implementation with the Serverless Framework.
- [IoT with the Serverless Framework](https://serverless.zone/iot-with-the-serverless-framework-e228fae87be#.1sd7ai8e5) - Blog post on how to use AWS IoT with Serverless.
- [Building a better Australian census site](http://blog.serverless.com/challenge-accepted-building-a-better-australian-census-site-with-serverless-architecture) - Interview which describes how two guys build an infinitely scalable serverless version of the Australian census web application on a weekend hackathon.
- [Meet the Serverless partner Parall.ax](http://blog.serverless.com/introducing-serverless-partners-meet-parallax) - Story on how the Serverless partner Parall.ax built the David Guetta "This one's for you" campaign with Serverless.
- [An abstracted serverless microservices architecture](https://serverless.zone/an-abstracted-serverless-microservices-architecture-33706fabc516#.xgpwlpie4) - Post which discusses an architectural approach how one can manage Serverless applications in a microservice way (with decoupled services).
- [What is serverless?](https://auth0.com/blog/what-is-serverless/) - Auth0 blog post which describes what the serverless architecture is.
- [Creating Marbot](https://cloudonaut.io/marbot-aws-serverless-chatbot-competition/) - Creating a Serverless chatbot called "Marbot".
- [Building a Facebook Messenger Chatbot](http://blog.serverless.com/building-a-facebook-messenger-chatbot-with-serverless/) - Tutorial how you can build a Facebook Messenger Chatbot with Serverless.
- [Unit and integration testing for Lambda](https://serverless.zone/unit-and-integration-testing-for-lambda-fc9510963003#.3xzvh5juk) - How to do unit and integration tests with AWS Lambda.
- [What makes serverless so attractive?](https://developer.ibm.com/opentech/2016/09/06/what-makes-serverless-attractive/) - Post which explains the benefits you get with a serverless architecture.
- [Creating your first Serverless app](http://blog.altoros.com/creating-your-first-serverless-app-with-aws-lambda-and-the-serverless-framework.html) - Overview of the different serverless providers with an example usage of the Serverless Framework.
- [Building a serverless screenshot service](http://svdgraaf.nl/2016/09/28/Serverless-Screenshot-Service-With-Lambda.html) - Building a serverless screenshot service.
- [Essential guide to serverless technologies](http://techbeacon.com/essential-guide-serverless-technologies-architectures) - Guide which goes into detail about the serverless technology / architecture.
- [Guide to serverless backend technologies](http://thenewstack.io/guide-serverless-technologies-functions-backends-service/) - A compilation of the best of FaaS and BaaS.
- [MoonMail technology stack](https://blog.moonmail.io/what-is-the-technology-stack-and-architecture-behind-moonmail-4d7d6a113ed6#.r2i0cxph6) - Post about the architecture of the [MoonMail](https://github.com/microapps/MoonMail) open source project.
- [Why enterprises should care about serverless computing](http://www.forbes.com/sites/janakirammsv/2016/10/12/why-enterprises-should-care-about-serverless-computing) - Post which outlines the future of serverless computing and enterprises.
- [Serverless v1 and fundraising](https://serverless.com/blog/releasing-serverless-framework-v1-and-fundraising/) - Blog post which announces Serverless v1 and the fundraising behind Serverless, Inc.
- [Serverlss raises $3M to help developers go serverless](https://techcrunch.com/2016/10/12/serverless-raises-3m-to-help-developers-go-serverless/) - TechCrunch article about the fundraising and future of Serverless, Inc.
- [Serverless, Inc. launches management framework](http://www.itbusinessedge.com/blogs/it-unmasked/serverless-inc.-launches-management-framework.html) - Post on the launch of Serverless v1 and upcoming plans.
- [Serverless Nets $3M to radically simplify cloud infrastructure](http://www.businesswire.com/news/home/20161012005381/en/Serverless-Nets-3M-Radically-Simplify-Cloud-Infrastructure) - BusinessWire article about the Serverless v1 launch.
- [Bustles serverless architecture](http://thenewstack.io/bustle-migrated-100-million-events-per-day-product-serverless/) - How Bustle uses a serverless architecture to manage 52 Mio. monthly visitors.
- [The Serverless Framework & GraphQL](http://www.heavybit.com/library/blog/the-serverless-framework-graphql) - Heavybit blog post about the Serverless GraphQL Meetup SF 06.10.2016.
- [A look at Serverless GraphQL](https://www.trek10.com/blog/a-look-at-serverless-graphql) - Trek10 article about using Serverless with GraphQL.
- [Serverless takes pain out of Lambda deployment](http://www.infoworld.com/article/3131004/cloud-computing/serverless-framework-takes-the-pain-out-of-aws-lambda-deployment.html) - Infoworld article about the Serverless v1 release.
- [Serverless and JAM (Part 2)](https://www.netlify.com/blog/2016/10/13/serverless-jam---a-serverless-framework-tutorial-part-2/) - Tutorial on how to use Serverless with the JAMstack (Part 2).
- [Developing Lambda applications with Eclipse](http://cloudacademy.com/blog/how-to-develop-lambda-applications-aws-toolkit-eclipse) - How to develop AWS Lambda applications with AWS toolkit for Eclipse.
- [Technology behind MoonMail](https://blog.moonmail.io/what-is-the-technology-stack-and-architecture-behind-moonmail-4d7d6a113ed6#.4sc9bb3fu) - What is the technology stack and architecture behind MoonMail?
- [Serverless with Java 8 and DynamoDB](https://medium.com/aws-activate-startup-blog/serverless-architectures-with-java-8-aws-lambda-and-amazon-dynamodb-part-1-fde79a6fb3cf#.48axcvvay) - Blog post series about a serverless setup with Java 8 and DynamoDB.
- [Serverless basic security](https://foobar123.com/serverless-security-594942b496ec#.y8xjoi7n6) - Introduction to serverless and security.
- [Serverless and TypeScript](https://gregshackles.com/getting-started-with-serverless-and-typescript/) - Getting started guide on how to use Serverless and TypeScript.
- [Meet the Serverless partner Trek10](https://serverless.com/blog/introducing-serverless-partners-meet-trek10/) - Introduction of the people behind the Serverless specalized agency Trek10.
- [Future of Serverless after v1.0](https://serverless.com/blog/serverless-post-1.0/) - The Serverless team shares their future improvements for the Serverless Framework.
- [Building a serverless screenshot service](https://medium.com/serverless-stories/building-a-serverless-screenshot-service-with-lambda-bf4dd151877#.8mg0psckq) - Tutorial how one can build a Screenshot service which runs 100% serverless.
- [Adopting serverless - People and DevOps](https://read.acloud.guru/adopting-serverless-people-and-devops-336e3ab89e96#.wjs11rf9j) - Things to be aware of when adpoting a serverless architecture in your organization.
- [Integration test serverless architectures](https://serverless.zone/monkeyless-chaos-integration-testing-for-serverless-architectures-9d1a4208c3ca#.5xmrbdqui) - Post which explains how to integration test a serverless application based on the "ChaosMonkey" approach Netflix uses.
- [Getting started with Serverless Tweet](https://twitter.com/slecache/status/789613648339673088) - Most minimal "Getting started with Serverless" tutorial.
- [The Serverless Framework is not serverless](https://medium.com/@PaulDJohnston/the-serverless-framework-is-not-serverless-5008ef67f547#.oteafe4d0) - Post about the difference between the serverless architecture and the Serverless Framework.
- [Building a serverless garden](https://serverless.com/blog/building-a-serverless-garden/) - Building A Serverless Garden Monitoring System with Lambda.
- [Path parameters with Serverless](https://foobar123.com/path-parameters-with-serverless-framework-7f0953d1dfa1#.ww1vx3t1a) - Post which explains how to use path parameters with the Serverless Framework.
- [Serverless security vulnerabilities](https://snyk.io/blog/Serverless-Security-Vulnerabilities/) - Post which discusses the different security vulnerabilities you need to be aware of when developing your serverless application.
- [Best serverless frameworks and tools](http://thenewstack.io/tns-guide-serverless-technologies-best-frameworks-platforms-tools/) - Overview of all the different serverless frameworks, tools and services.
- [Look ma, No server](http://www.wsj.com/articles/look-ma-no-server-corporate-it-expects-serverless-computing-to-trigger-big-changes-1477509674) - Wall Street Journal post about the future of serverless architectures in corporate contexts.
- [Shifter goes serverless](http://cloudacademy.com/blog/wordpress-cloud-hosting-shifter) - Story how the [Shifter platform](https://beta.getshifter.io/) went to a serverless architecture.
- [ServerlessConf 2016 recap](https://serverlesscode.com/post/serverlessconf-london-recap/) - Recap of the ServerlessConf 2016 in London.
- [Serverless v1.1.0](https://serverless.com/blog/serverless-v1.1.0/) - Release blog post about Serverless v1.1.0.
- [4 Ways to secure Serverless Applications with Snyk](https://serverless.com/blog/4-ways-to-secure-prevent-vulnerabilities-in-serverless-applications/) - 4 ways to prevent vulnerabilities in Serverless applications.
- [What's missing](https://serverless.zone/serverlessconf-8cbc8bc52986#.op8mo24l3) - Post which outlines what features are missing in the serverless world.
- [Serverless Map / Reduce](http://tothestars.io/blog/2016/11/2/serverless-mapreduce) - Showcase on how to use Lambda for Map / Reduce operations.
- [Serverless notifications on AWS](http://zanon.io/posts/serverless-notifications-on-aws) - How to use the Serverless Framework and AWS IoT for Serverless Notifications.
- [Getting dirty with Serverless v1](https://blog.gorillastack.com/getting-dirty-with-serverless-framework-v1-part-1-redirects) - Experiences and learnings gained during a transition from Serverless v0 to v1.
- [Serverless video service](https://medium.com/@federicopanini/video-content-generated-solution-with-aws-lambda-ccb5d5d4629c#.3ktcgkdrx) - How to create a ready-to-use application where users can upload video contents.
- [My opinion on Serverless](https://cloudonaut.io/my-opinion-on-serverless/) - Opinion from the guys at [Cloudonaut](cloudonaut.io) about the serverless movement.
- [Save a file in S3](https://foobar123.com/serverless-save-a-file-in-s3-using-aws-lamdba-d3f087880dd2#.fh7u6fjej) - Post which shows how to save a file to S3 when using a serverless architecture.
- [Smart persons guide to serverleess computing](http://www.techrepublic.com/article/serverless-computing-the-smart-persons-guide) - Guide which covers what serverless computing is and how it could reduce the complexity and cost of your cloud infrastructure.
- [Prod-To-Staging Data Pipeline](https://serverlesscode.com/post/lambda-rds-prod-staging-pipeline) - How to use Serverless to migrate data from production to staging using Yesterdaytabase.
- [Keeping the Serverless Framework up to date](https://foobar123.com/keep-your-serverless-framework-up-to-date-b6af35d4cf77#.ef32fvad6) - Tutorial which shows you what to do to use the most recent version of the Serverless Framework.
- [Serverless Architecture](https://briantroy.com/2016/10/11/series-part-1-serverless-architecture-a-practical-implementation-iot-device-data-collection-processing-and-user-interface) - Multi part blog post series about the serverless architecture (starts with a serverless IoT setup).
- [Adopting serverless](https://read.acloud.guru/adopting-serverless-outsourcing-4e4a4a54f218#.b986oa89h) - Factors to consider when choosing a serverless architecture.
- [CloudSploits switch to serverless](https://blog.cloudsploit.com/we-made-the-whole-company-serverless-5a91c27cd8c4#.a59q4jmle) - Interesting read on how CloudSploit made their whole company run serverless.
- [AWS CLI inside of Lambda](https://alestic.com/2016/11/aws-lambda-awscli) - Tutorial how you can run `aws-cli` commands within a Lambda function.
- [3 ways serverless changes app development 2017](http://www.forbes.com/sites/ibm/2016/11/17/three-ways-that-serverless-computing-will-transform-app-development-in-2017/#13483a46565a) - Post how serverless computing will transform app development in the future.
- [Serverless PHP](http://blog.zerosharp.com/the-serverless-framework-and-php/) - How to call PHP functions from AWS Lambda.
- [Top tips for writing Serverless plugins](http://red-badger.com/blog/2016/11/21/top-tips-for-writing-serverless-plugins) - Blog post about tips and tricks for writing Serverless Framework plugins.
- [Serverless env variables](https://serverlesscode.com/post/env-vars-support-lambda) - Tutorial how you can use AWS Lambda environment variables with the Serverless Framework.
- [Building an awesome developer community](https://serverless.com/blog/lessons-learned-on-building-awesome-developer-community) - Blog post by the Serverless team about lessons learned while building a developer community.
- [Cloud trends](https://medium.com/@adrianco/cloud-trends-where-have-we-come-from-and-where-are-we-headed-3d7e5e756d16#.hzlrb8d3m) - Post by Adrian Cockcroft about the development of cloud trends in retrospect and the future.
- [Why the fuss about Serverless](https://medium.com/@swardley/why-the-fuss-about-serverless-4370b1596da0#.genbkobbc) - In-depth blog post which explains why Serverless is such a hot topic nowadays.
- [Going Serverless at BandLab](https://serverless.com/blog/going-serverless-at-bandlab) - Blog post about better DevOps with AWS Lambda + API Gateway and the Serverless Framework.
- [State of the serverless community](https://serverless.com/blog/state-of-serverless-community) - Results of the Serverless community survey.
- [A concrete PHP Serverless example](http://blog.zerosharp.com/a-concrete-php-serverless-example) - Export chess games in PDF using PHP.

## Screencasts

- [Hands on with Serverless v1](http://blog.rowanudell.com/hands-on-with-serverless-v1-screencast/) - Rowan Udell shows how to get started with Serverless v1.

## Talks

- [JAWS @ re:Invent YouTube Video](https://www.youtube.com/watch?v=D_U6luQ6I90) - Presentation video of the re:Invent talk.
- [JAWS @ re:Invent presentation slides](http://de.slideshare.net/AmazonWebServices/dvo209-jaws-a-scalable-serverless-framework) - Presentation slides of the re:Invent talk.
- [The dot Post](http://www.thedotpost.com/2015/12/nicolas-grenie-serverless-microservices-in-javascript) - The dot Post with a presentation about Serverless.
- [Serverless computing](https://www.youtube.com/watch?v=iQzd7TkKlnI) - Intro to Serverless computing.
- [What is the serverless architecture?](https://www.youtube.com/watch?v=IDm71SR58xw) - The serverless architecture explained.
- [SC5 workshop](https://sc5.io/posts/apidays-nordic-2016-aws-serverless-workshop/) - SC5 AWS / Serverless workshop.
- [Deep dive on Serverless web applications](https://www.youtube.com/watch?v=fXZzVzptkeo) - AWS intro to serverless computing.
- [Serverless Framework with Austen Collins](http://softwareengineeringdaily.com/2016/06/09/serverless-framework-austen-collins/) - Podcast about the Serverless framework.
- [Serverless Meetup London 07.2016](https://www.youtube.com/watch?v=kIpjBof5fBE) - Video of the first Serverless meetup in London.
- [Lambda Functions and Serverless Architectures](https://www.youtube.com/watch?v=9qkb_OrjRRc) - Talk about Lambda, AWS and the Serverless framework.
- [Use Cases & Architectures](https://www.youtube.com/watch?v=Ek5fIWgkXbI) - Trek10 talk about different use cases and serverless architectures
- [Serverless and GraphQL](https://www.youtube.com/watch?v=Fk--XUEorvc&t=3h32m) - React Rally talk about Serverless and GraphQL by Kevin Old.
- [Serverless architectures with Mike Roberts](http://softwareengineeringdaily.com/2016/08/23/serverless-architecture-with-mike-roberts/) - Software Engineering Daily podcast about the Serverless architecture.
- [Building a serverless architecture](https://www.youtube.com/watch?v=vXHkruxonm0) - Rackspace talk on how to build a serverless architecture on AWS.
- [Serverless less server](https://speakerdeck.com/mhausenblas/serverless-less-server/) - Slides of the "Serverless less server" talk.
- [How Serverless is reshaping AWS Lambda](http://thenewstack.io/how-serverless-is-reshaping-aws-lambda/) - Podcast with Austen Collins (creator of Serverless) about v1 of the Serverless Framework.
- [Serverless v1 Fullstack Fest 2016 talk](https://www.youtube.com/watch?v=9IrFIobZUEA) - Talk about the Serverless Framework on the Fullstack Fest conference.
- [Apigee and Autodesks talk on Serverless Microservices](https://www.youtube.com/watch?v=Jtc4RWaRHX4) - Autodesk explains how they're transforming their architecture to be serverless.
- [Serverless microservices](https://www.youtube.com/watch?v=w14NJkV5yAg) - General talk about serverless microservices by Ben Vandgrift and Adam Hunter.
- [Building with the Serverless Framework](https://www.youtube.com/watch?v=BKx9vxxuZXY) - Austen Collins shows how one can build applications with the Serverless Framework.
- [Serverless GraphQL Meetup SF](https://www.youtube.com/watch?v=B7SUJwvw6EI) - Serverless GraphQL Meetup SF 06.10.2016.
- [Build reactive systems on Lambda](http://www.slideshare.net/theburningmonk/build-reactive-systems-on-lambda) - Presentation about the first steps with AWS Lambda.
- [JAMstack Radio podcast about the Serverless Framework](http://www.heavybit.com/library/podcasts/jamstack-radio/ep-4-the-serverless-framework-and-aws-lambda/) - David Wells from Serverless, Inc. talks about the Serverless Framework.
- [The Future of PAAS is Serverless](https://www.youtube.com/watch?v=AtJUYSzksp0) - Talk about serverless architectures and the Serverless Framework.

## Amazon AWS resources

- [Amazon AWS homepage](http://aws.amazon.com) - Official Amazon AWS homepage.
- [Free Amazon AWS tier](http://aws.amazon.com/free) - Highly recommended to get started with Amazon AWS.
- [AWS S3](https://aws.amazon.com/s3) - File storage solution (used to server files such as HTML or JavaScript).
- [AWS Lambda](https://aws.amazon.com/lambda/details) - Details about the Lambda service.
- [AWS Cloudformation](https://aws.amazon.com/cloudformation/) - Details about CloudFormation.
- [AWS API Gateway](https://aws.amazon.com/api-gateway/) - Details about API Gateway.
- [AWS IAM](https://aws.amazon.com/iam/) - Details about Identity and Access Management (IAM).
- [Cloudcraft](https://cloudcraft.co/) - Awesome tool to plan and visualize your AWS infrastructure.

## Projects / Services

- [Serverless examples](https://github.com/serverless-examples) - GitHub organization with several Serverless example projects.
- [React Serverless](https://github.com/hiromoon/react-serverless) - Use React together with Serverless.
- [Serverless test plugin](https://github.com/arabold/serverless-test-plugin) - Test plugin.
- [Lang Adventure backend](https://github.com/jonatasschagas/langadventurebackend) - Backend from Lang Adventure game.
- [Serverless project written with ES2015](https://github.com/mpppk/serverless-project-written-in-es2015) - Project example written in ES2015.
- [Serveress Telegram bot](https://github.com/minibikini/serverless-telegram-bot) - Telegram bot implementation.
- [Serverless pre register](https://github.com/agentmilindu/Serverless-Pre-Register) - Product Pre-registration page.
- [Serverless mapbox classic](https://github.com/LukeSwart/serverless-mapbox-classic) - API gateway that munges geojson coming from a mapbox classic editor.
- [Universal Serverless React](https://github.com/jstrutz/universal-serverless-react) - React with Serverless.
- [Serverless example](https://github.com/iblue/serverless-example) - Experimental example project.
- [DynamoDB CRUD example](https://github.com/jagthedrummer/serverlessDynamoCrudExample) - How to use DynamoDB with Serverless.
- [GraphQL Blog](https://github.com/serverless/serverless-graphql-blog) - A Blog powered by GraphQL and Serverless.
- [Password of the day](https://github.com/ZeroSharp/ServerlessPotd) - Password of the day service. Utilizing TypeScript.
- [func4](https://github.com/ac360/func4) - Show and create users.
- [Boxify](https://github.com/jankei/boxify) - Boxify API service.
- [MIDAAS API](https://github.com/presidential-innovation-fellows/midaas-api) - MIDAAS API.
- [Zanon IO Demo](https://github.com/zanon-io/aws-serverless-demo) - Demo project.
- [Cortex](https://github.com/namastereid/cortex) - Cortex project.
- [Protocol service](https://github.com/Backfeed/protocol-service) - Protocol service.
- [Cat facts](https://github.com/ryansb/serverless-cat-facts) - Example how to use Serverless with Python.
- [Notes](https://github.com/JustServerless/notes) - Note taking application written for the ["Learn Serverless"](http://learnserverless.club) book.
- [Aquest](https://github.com/dherault/Aquest) - Demo application.
- [Hello world](https://github.com/bart-blommaerts/serverless_helloworld) - Hello World application.
- [Garage](https://github.com/bart-blommaerts/serverless_garage) - Managing cars.
- [Slackbot scaffold](https://github.com/localytics/serverless-slackbot-scaffold) - Scaffold for a Serverless slackbot.
- [Lambda-React-SSR](https://github.com/dherault/Lambda-React-SSR/) - Server-side rendering with React on Lambda.
- [Authentication boilerplate](https://github.com/laardee/serverless-authentication-boilerplate) - Authentication boilerplate for Serverless.
- [Blog](https://github.com/charltones/serverless_blog) - Blog example using Serverless.
- [MoonMail](https://github.com/microapps/MoonMail) - Serverless newsletter service.
- [Serverless GraphQL boilerplate](https://github.com/serverless/serverless-graphql) - Official Serverless GraphQL boilerplate.
- [SC5 boilerplate](https://github.com/SC5/sc5-serverless-boilerplate) - Serverless boilerplate by SC5.
- [Facebook messenger chatbot](https://github.com/JustServerless/serverless-facebook-messenger-chatbot) - Facebook messenger chatbot who searches for GitHub repositories.
- [Facebook messenger bot](https://github.com/michalsanger/serverless-facebook-messenger-bot) - Feature rich Facebook messenger chatbot.
- [Discuss](https://github.com/JustServerless/discuss) - Forum software powered by Serverless, GraphQL, React and Redux.
- [Elasticommerce search service](https://github.com/amimoto-ami/serverless-elasticommerce-search-service) - Elasticsearch service for WooCommerce shops.
- [Serverless starter Python](https://github.com/alexcasalboni/serverless-starter-python) - Starter project for Python based project.
- [Serverless (v1.0) Python Sample](https://github.com/bennybauer/serverless-python-sample) - A simple Serverless Python sample with REST API endpoints and dependencies.
- [Express to AWS Lambda](https://github.com/johncmckim/express-to-aws-lambda) - Code of the "Express to AWS Lambda" blog post series.
- [Serverless HipChat connect](https://bitbucket.org/gorillastack/serverless-hipchat-connect) - Using Atlassian connect with Serverless.
- [Serverless MongoDB](https://github.com/pcorey/serverless-mongodb/) - Example project on how to use Serverless and MongoDB.
- [Serverless npm registry](https://github.com/mgrenier/serverless-npm-registry) - Npm registry built with the help of the Serverless framework.
- [AWS Serverless SoundCloud](https://github.com/trunghieu138/aws-serverless-soundcloud) - Get artists tracks from SoundCloud.
- [PhantomJS Lambda pack](https://github.com/justengland/phantomjs-lambda-pack) - PhantomJS wrapper for AWS Lambda.
- [Garden Aid](https://github.com/garden-aid) - Serverless IoT project to track gardening related data.
- [Serverless Cloud Vision](https://github.com/ramhiser/serverless-cloud-vision) - A project which uses Google Cloud Vision together with the Serverless framework.
- [Wolfram Lambda](https://bitbucket.org/pstreule/wolfram-lambda) - HipChat Chatbot which integrates with WolframAlpha.
- [Yith](https://github.com/craftship/yith) - Serverless private npm registry.
- [Trevorbot](https://github.com/conveyal/trevorbot) - Slackbot which will say you where Trevor is.
- [Quotebot](https://github.com/pmuens/quotebot) - Facebook Messenger chatbot which will return a random quote on message retrieval.
- [Weekly2Pocket](https://github.com/s0enke/weekly2pocket) - Saves weekly stories to the Pocket app.
- [Pokégo serverless](https://github.com/jch254/pokego-serverless) - Serverless-powered API to fetch nearby Pokemon Go data.
- [Serverless Example](https://github.com/andymac4182/serverless_example) - Different, feature rich examples for Serverless v1.
- [Serverless microservice architecture](https://gitlab.com/patoncrispy/serverless-sample-app) - Code which demonstrates a Serverless microservice architecture with decoupled Services.
- [Serverless Zwiftalizer](https://github.com/mhanney/serverless-zwiftalizer) - Serverless project which includes Lambda functions to support the Zwiftalizer frontend.
- [React boilerplate](https://github.com/99xt/serverless-react-boilerplate) - React boilerplate for applications which are powered by Serverless and React.
- [Serverless screenshot](https://github.com/svdgraaf/serverless-screenshot) - Code for a screenshot service build with Serverless.
- [Serverless minimal](https://github.com/mthenw/serverless-minimal) - The smallest possible Serverless service.
- [Serverless authorizer](https://github.com/eahefnawy/serverless-authorizer) - Example of a service that uses API Gateway custom authorizer feature to authorize your endpoints.
- [Serverless artillery](https://github.com/Nordstrom/serverless-artillery) - Instant and cheap performance testing at scale (combines [Serverless](http://serverless.com) and [Artillery](http://artillery.io)).
- [Delivery Framework](https://github.com/99xt/serverless-delivery-framework) - Boilerplate for version release pipeline with the Serverless Framework.
- [Serverless Beer](https://github.com/cassiozen/serverless-beer) - Example application which uses DynamoDB.
- [CRUD](https://github.com/pmuens/serverless-crud) - CRUD service.
- [Mailer](https://github.com/eahefnawy/serverless-mailer) - Service for sending E-Mails.
- [Kinesis streams](https://github.com/pmuens/serverless-kinesis-streams) - Service to showcase Kinesis stream support.
- [DynamoDB streams](https://github.com/pmuens/serverless-dynamodb-streams) - Service to showcase DynamoDB stream support.
- [Landingpage backend](https://github.com/pmuens/serverless-landingpage-backend) - Landingpage backend service to store E-Mail addresses.
- [Facebook Messenger Chatbot](https://github.com/pmuens/serverless-facebook-messenger-bot) - Chatbot for the Facebook Messenger platform.
- [Lambda chaining](https://github.com/pmuens/serverless-lambda-chaining) - Service which chains Lambdas through SNS.
- [Secured API](https://github.com/pmuens/serverless-secured-api) - Service which exposes an API key accessible API.
- [Authorizer](https://github.com/eahefnawy/serverless-authorizer) - Service that uses API Gateway custom authorizers.
- [Thumbnails](https://github.com/eahefnawy/serverless-thumbnails) - Service that takes an image url and returns a 100x100 thumbnail.
- [Boilerplate](https://github.com/eahefnawy/serverless-boilerplate) - Opinionated boilerplate.
- [Serverless Sharp Image](https://github.com/adieuadieu/serverless-sharp-image) - function triggered by S3 events to resize images with the awesome Sharp library
- [Serverles Artillery workshop](https://github.com/Nordstrom/serverless-artillery-workshop) - Step by step workshop to create a load testing service which combines [Serverless](http://serverless.com) and [Artillery](http://artillery.io).
- [ServerlessConf workshop](https://github.com/ServerlessInc/serverlessconf-workshop) - Project code for the ServerlessConf London 2016 workshop.
- [Messenger boilerplate](https://github.com/SC5/serverless-messenger-boilerplate) - Serverless messenger bot boilerplate.
- [ES6 + Jest](https://github.com/americansystems/serverless-es6-jest) - Serverless framework with ES6 via Webpack + Babel + Jest.
- [CRUD Scala](https://github.com/jahangirmohammed/serverless-crud-scala) - CRUD example which uses Scala and the Java runtime.
- [Generator Serverless service](https://github.com/ACloudGuru/generator-serverless-service) - A scaffold for a Node.js Serverless service.
- [SalckNorris](https://github.com/robertoestivill/slacknorris) - Slack command to retrieve great Chuck Norris quotes.
- [Web API scaffold](https://github.com/jch254/serverless-es6-dynamodb-webapi) - Simple web API powered by Serverless (Node.js) and DynamoDB.
- [Serverless Notifications](https://github.com/zanon-io/serverless-notifications) - Project which uses the Serverless Framework and AWS IoT for notifications.
- [Redirect example](https://github.com/GorillaStack/serverless-redirect-example) - Example of how to implement redirects in the Serverless framework.
- [Meetup event collector](https://github.com/mavi888/meetup-event-collector-node) - Node project to collect events and create a calendar feed of meetup events.
- [Yesterdaytabase](https://github.com/ryansb/yesterdaytabase) - Cascade data from production to staging with AWS RDS and Lambda.
- [Serverless dotenv WSGI](https://github.com/braahyan/serverless-dotenv-wsgi) - Demonstrating the use of the `serverless-wsgi` plugin and the `serverless-plugin-dotenv` plugin.
- [Serverless PHP](https://github.com/ZeroSharp/serverless-php) - Example using an AWS Lambda which runs a PHP function.
- [Newsletter Signup](https://github.com/ivanderbu2/serverless-newsletter-signup) - Newsletter Signup API in Serverless.
- [Express Serverless Boilerplate](https://github.com/SharathHuddar/express-serverless-boilerplate) - A simple boilerplate for using expressjs with serverless v1.2.1.
- [GraphQL Dad Jokes](https://github.com/kevinold/serverless-graphql-dadjokes) - Example Serverless GraphQL v1.0 "Dad Jokes" service from React Rally 2016.
- [Serverless HTTP](https://github.com/dougmoscrop/serverless-http) - Middleware wrapper for serverless use.

## Related projects

- [DataFire](https://github.com/DataFire/DataFire) - Open Integration Framework.
- [AWS log parser](https://github.com/rotemtam/serverless-aws-logs-parser) - Make sense of Lambda and API Gateway CloudWatch log files.
- [IronFunctions](https://github.com/iron-io/functions) - The Serverless Microservices Platform.

## Plugins

- [Webpack](https://github.com/elastic-coders/serverless-webpack) - Plugin to add webpack to Serverless.
- [Scriptable](https://github.com/wei-xu-myob/serverless-scriptable-plugin) - Make Serverless scriptable without writing a Plugin.
- [Build plugin](https://github.com/nfour/serverless-build-plugin) - Optimizes your Node.js functions before they're deployed.
- [Write env vars](https://github.com/silvermine/serverless-plugin-write-env-vars) - Access environment variables in Lambda functions.
- [Alexa plugin](https://github.com/rajington/serverless-alexa-plugin) - Support Alexa Lambda events.
- [Multi responses](https://github.com/silvermine/serverless-plugin-multiple-responses) - Allow multiple content types in response templates.
- [Run function](https://github.com/lithin/serverless-run-function-plugin) - Plugin to run your Serverless functions locally.
- [Stage variables](https://www.npmjs.com/package/serverless-plugin-stage-variables) - Add stage variables for Serverless 1.x to ApiGateway, so you can use variables in your Lambda's.
- [DynamoDB local](https://github.com/99xt/serverless-dynamodb-local/tree/v1) - Allows to run dynamodb locally for Serverless.
- [Stack outputs](https://www.npmjs.com/package/serverless-plugin-stack-outputs) - Plugin that outputs all stack outputs.
- [Command line event args](https://github.com/horike37/serverless-command-line-event-args) - Inline event.json for the invoke plugin.
- [WSGI](https://github.com/logandk/serverless-wsgi) - Helps you to deploy Python WSGI applications (Flask/Django etc.).
- [External SNS events](https://github.com/silvermine/serverless-plugin-external-sns-events) - Let you use an already existent SNS topic as the event source.
- [CloudWatch Sumologic](https://github.com/ACloudGuru/serverless-plugin-cloudwatch-sumologic) - Plugin which auto-subscribes a log delivery Lambda function to lambda log groups created by Serverless.
- [Browserify](https://github.com/doapp-ryanp/serverless-plugin-browserify) - Add browserify to speedup Lambdas.
- [Optimize](https://github.com/FidelLimited/serverless-plugin-optimize) - Optimize plugin for Serverless.
- [Include dependencies](https://github.com/dougmoscrop/serverless-plugin-include-dependencies) - Explicitly include packages in your `node_modules` folder.
- [Subscription filter](https://github.com/blackevil245/serverless-subscription-filter) - Register subscription filter for Lambda logs.
- [Snyk plugin](https://github.com/Snyk/serverless-snyk) - Plugin for securing your dependencies with Snyk.
- [CloudWatch logging subscriptions](https://github.com/TicketSolutionsPtyLtd/serverless-plugin-cloudwatch-logging-subscriptions) - Adds CloudWatch log subscriptions for each function in a Serverless service.
- [Crypt](https://github.com/marcy-terui/serverless-crypt) - Securing Serverless secrets by AWS KMS encryption.
- [Diff](https://github.com/nicka/serverless-plugin-diff) - Compares your local AWS CloudFormation templates against deployed ones.
- [Rollback function](https://github.com/marcy-terui/serverless-rollback-function) - Rollback a single function.
- [CloudFormation Authorizer](https://github.com/SC5/serverless-plugin-cfauthorizer) - Define your own API Gateway Authorizers as the Serverless CloudFormation resources and apply them to HTTP endpoints.
- [Babel](https://github.com/serverless/serverless-babel-plugin) - Plugin to compile your JavaScript code with Babel before deployment.
- [External S3 event](https://github.com/matt-filion/serverless-external-s3-event) - Overcomes the CloudFormation limitation on attaching an event to an uncontrolled bucket.
- [Inspect](https://github.com/SEEK-Jobs/serverless-plugin-inspect) - Get AWS stack info in JSON.
- [IBM OpenWhisk](https://github.com/serverless/serverless-ibm-openwhisk) - Adds IBM OpenWhisk support to the Serverless Framework.
- [Google Cloud Functions](https://github.com/serverless/serverless-google-cloudfunctions) - Adds Google Cloud Functions support to the Serverless Framework.
- [Azure Functions](https://github.com/serverless/serverless-azure-functions) - Add Azure Functions support to the Serverless Framework.

## Literature

- [Serverless book - By the Serverless team](https://github.com/pmuens/serverless-book) - Book focused on v1 of the [serverless.com](http://serverless.com) framework.
- [Serverless - By Obie Fernandez](https://leanpub.com/serverless) - Book about Serverless development (also covers usage of the Serverless framework).
- [Serverless Architectures on AWS - By Peter Sbarski & Sam Kroonenburg](http://book.acloud.guru) - Book focused on covering serverless architectures using AWS.

## Professional services

- [Trek10](http://trek10.com) - Consultancy.
- [Parallax](https://parall.ax/) - Consultancy.
- [SC5 Online](https://sc5.io) - Serverless agency.
- [Carrot creative](https://carrot.is) - Agency.
- [Microapps](http://microapps.com) - Agency.
- [Apiwise](http://www.apiwise.nl) - Agency.
- [Useful.io](http://useful.io) - Agency.
- [WhaleTec](https://whaletech.co) - Consultancy.
- [Hop Labs](http://hoplabs.com) - Consultancy.
- [Webscale](https://webscale.fi/briefly-in-english/) - Consultancy.
- [API talent](http://www.apitalent.co.nz) - Consultancy.
- [Branded Crate](https://www.brandedcrate.com/) - Agency.
- [Cloudonaut](https://cloudonaut.io/serverless-consulting/) - Consultancy.
- [PromptWorks](https://www.promptworks.com/serverless/) - Consultancy.
- [Craftship](https://craftship.io) - Consultancy.
- [EPX Labs](http://www.epxlabs.com) - Consultancy.

---

## Deprecated

> Deprecated stuff. Kept for completeness.

### General

- [Community repository](https://github.com/serverless/serverless-community) - Resources for the community.
- [Readme.io](https://serverless.readme.io) - Official documentation.
- [Community plugins](https://github.com/serverless/community-plugins) - Repository for Serverless community plugins.
- [AWSM](https://github.com/awsm-org/awsm) - Official GitHub organization for modules.
- [Getting started with JAWS on AWS](https://aws.amazon.com/de/blogs/compute/getting-started-with-jaws-on-amazon-web-services/) - Getting started guide with Serverless by Amazon (might be deprecated).
- [Serverless starter](https://github.com/serverless/serverless-starter) - Boilerplate for new projects.
- [JAWS local server](https://github.com/martinlindenberg/JawsLocalServer) - Local server which lets you execute Lambda functions locally.
- [Shark Notes](https://github.com/JustServerless/shark-notes) - Full note taking tool (frontend and backend) which shows how to do CRUD with Serverless.
- [Serverless Registry](https://justserverless.github.io/serverless-registry) - Unofficial plugin and module search.

### Projects (v0.5)

- [Demo with DynamoDB](https://github.com/abalone0204/serverless-demo-with-dynamodb-node) - Simple REST API with the Serverless Framework.

### Plugins (v0.5)

- [Plugin boilerplate](https://github.com/serverless/serverless-plugin-boilerplate) - Boilerplate code if you want to develop your own plugin.
- [Serverless resources validation](https://github.com/tmilewski/serverless-resources-validation-plugin) - Plugin which validates your CloudFormation template.
- [Alerting](https://github.com/martinlindenberg/serverless-plugin-alerting) - Add Cloudwatch Alarms with SNS notifications.
- [Lambda prune](https://github.com/Nopik/serverless-lambda-prune-plugin) - Automatically remove unused Lambda functions.
- [Autoprune](https://github.com/kennu/serverless-plugin-autoprune) - Automatically remove unused Lambda functions.
- [Swagger](https://github.com/marklawlor/serverless-swagger) - Swagger.io plugin.
- [CORS](https://github.com/joostfarla/serverless-cors-plugin) - CORS plugin.
- [Serve](https://github.com/Nopik/serverless-serve) - Test your lambda functionality locally.
- [Base path plugin](https://github.com/daffinity/serverless-base-path-plugin) - Setting a base path for all API Gateway endpoints in a component.
- [SNS](https://github.com/martinlindenberg/serverless-plugin-sns) - Plugin for SNS support.
- [Cronjob](https://github.com/martinlindenberg/serverless-plugin-cronjob) - Plugin for Cronjobs.
- [API Blueprint](https://github.com/hiroara/serverless-api-blueprint) - API documentation generator.
- [VPC](https://github.com/martinlindenberg/serverless-plugin-vpc) - VPC support.
- [Client S3](https://github.com/serverless/serverless-client-s3) - Handle static asset serving (like static frontends) via S3.
- [Offline](https://github.com/dherault/serverless-offline) - An alternative to the Serve plugin, with Velocity templates support.
- [Serverless optimizer](https://github.com/asprouse/serverless-optimizer-plugin) - Fork of the optimizer plugin which uses Webpack.
- [JSHint](https://github.com/joostfarla/serverless-jshint-plugin) - Detect errors and potential problems in your Lambda functions.
- [Webpack](https://github.com/asprouse/serverless-webpack-plugin) - Use Webpack to optimize your Serverless Node.js Functions.
- [Runtime Babel](https://github.com/serverless/serverless-runtime-babel) - Babel runtime for the Serverless framework (so that ES6 and ES7 syntax can be used).
- [Runtime Streamline](https://github.com/marclar/serverless-runtime-streamline) - Streamline.js for Serverless.
- [Meta Sync](https://github.com/serverless/serverless-meta-sync) - Synchronize project credentials via AWS.
- [GraphiQL](https://github.com/marclar/serverless-graphiql) - Deploys a GraphiQL client to a public S3 bucket.
- [S3](https://github.com/camhart/sls-s3) - Deploy files to S3.
- [Swagger](https://github.com/serverless/serverless-swagger-plugin) - Swagger plugin.
- [Synchronous resource](https://github.com/stelligent/serverless-synchronous-resource-plugin) - Plugin for deploying custom CFN stacks.
- [Models](https://github.com/HyperBrain/serverless-models-plugin) - Plugin for model support.
- [Mocha](https://github.com/SC5/serverless-mocha-plugin) - Plugin to use Mocha.js.
- [Package](https://github.com/HyperBrain/serverless-package-plugin) - Adds function packaging.
- [Sentry](https://github.com/arabold/serverless-sentry-plugin) - Sentry integration for Serverless.
- [Autoprune](https://github.com/arabold/serverless-autoprune-plugin) - Delete old lambdas.
- [Secrets](https://github.com/trek10inc/serverless-secrets) - Secret management.
- [Vandium](https://github.com/vandium-io/vandium-serverless) - Vandium PlugIn for Serverless.
- [Command line event args](https://github.com/horike37/serverless-command-line-event-args) - Pass JSON to serverless via the command line.
- [Unit test boilerplate](https://github.com/horike37/serverless-unittest-boilerplate) - Boilerplate for unit testing with Serverless.
- [Dependency install](https://github.com/99xt/serverless-dependency-install) - Serverless plugin for managing dependencies.
- [DynamoDB local](https://github.com/99xt/serverless-dynamodb-local) - Use DynamoDB locally with Serverless.
- [Cognito manager](https://github.com/trek10inc/serverless-cognito-manager) - Easy cognito management for Serverless projects.
- [Hook scripts](https://github.com/kennu/serverless-plugin-hookscripts) - Run code whenever a Serverless action is run.
- [Header function](https://github.com/blackevil245/serverless-header-function) - Automatically run a JavaScript script on every Serverless action hooks.

### Modules

- [npm registry](https://github.com/Inbot/awsm-npm-registry) - npm registry.
- [Users](https://github.com/dekz/awsm-users) - AWSM module for authentication.
- [Test AWS users library](https://github.com/oren/test-awsm-users) - Test AWSM users.
- [Stripe webhook](https://github.com/eahefnawy/serverless-stripe-webhook) - Webhook for Stripe payments.
- [Slack webhook](https://github.com/eahefnawy/serverless-slack-webhook) - Webhook for Slack.
- [Slack](https://github.com/serverless/serverless-slack) - Slack boilerplate functionality.
- [Examples](https://github.com/remicastaing/serverless-examples) - Module with example functions.
- [Slackbot](https://github.com/serverless/serverless-slackbot) - Module to create your own slackbot.
- [Images](https://github.com/awsm-org/awsm-images) - Image modifications.
- [Cloudfront](https://github.com/boushley/awsm-cloudfront) - Puts CloudFront distribution in front of your project.
- [S3 token vendor](https://github.com/binoculars/awsm-s3tokenvendor) - Return upload tokens for S3 objects.
- [Loggly](https://github.com/jwulf/awsm-loggly) - Provide logging to your lambdas.
- [Middleware](https://github.com/jwulf/awsm-middleware) - Middleware for your project.
- [GitHub Webhook](https://github.com/bisque33/awsm-github-webhook) - GitHub webhook support.
- [Comments](https://github.com/donleyp/awsm-comments) - Implements comments using DynamoDB.
- [3scale](https://github.com/jerzyn/awsm-3scale) - Integrates 3scale API management platform.

### Literature

- [Learn Serverless - By Philipp Müns](https://github.com/JustServerless/learnserverless-book) - Book focused on the serverless.com framework. **Note:** Deprecated.
