# Awesome Serverless [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of resources regarding the [Serverless project](https://github.com/serverless) (previously known as JAWS).

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list project.*

**Say *hello* on [Twitter](https://twitter.com/pmmuens).**

- [General](#general)
- [Blog posts](#blogs-blog-posts)
- [Talks](#talks)
- [Amazon AWS resources](#amazon-aws-resources)
- [Projects](#projects)
- [Plugins](#plugins)
- [Modules](#modules)
- [Literature](#literature)
- [Professional services](#professional-services)

---

## General

- [Homepage](http://serverless.com) - Official homepage
- [GitHub organization](http://github.com/serverless) - Official GitHub organization
- [Twitter](https://twitter.com/goserverless) - Official Twitter account
- [Readme.io](https://serverless.readme.io) - Official documentation
- [Vimeo](https://vimeo.com/user2421131) - JAWS Vimeo account
- [YouTube](https://www.youtube.com/channel/UCFYG383lawh9Hrs_DEKTtdg) - Serverless YouTube account
- [Community repository](https://github.com/serverless/serverless-community) - Resources for the community
- [AWSM](https://github.com/awsm-org/awsm) - Official GitHub organization for modules
- [Serverless Registry](https://justserverless.github.io/serverless-registry) - Unofficial plugin and module search
- [Roadmap](https://trello.com/b/EX6SxBJJ/serverless) - Trello roadmap
- [Meetups](http://www.meetup.com/serverless/) - Meetups
- [Stackoverflow](http://stackoverflow.com/questions/tagged/serverless) - Stackoverflow questions
- [Gitter Chat](https://gitter.im/serverless/serverless) - Chat with the community

## Blogs / blog posts

- [Just Serverless](http://justserverless.com/blog) - Blog about the Serverless framework
- [Infoword article](http://www.infoworld.com/article/2990795/cloud-computing/jaws-takes-a-bite-out-of-aws-lambda-app-deployment.html) - Infoworld blog post discussing Serverless (formerly known as JAWS)
- [Interview with the Parallax agency](https://serverlesscode.com/post/david-guetta-online-recording-with-lambda) - Interview how [This ones for you](http://thisonesforyou.com) was developed with the Serverless framework
- [Example AWS infrastructure](https://serverlesscode.com/images/guetta_article/image04.png) - Example cloud infrastructure for a Serverless project
- [Getting started with JAWS on AWS](https://aws.amazon.com/de/blogs/compute/getting-started-with-jaws-on-amazon-web-services/) - Getting started guide with Serverless by Amazon (might be deprecated)
- [Build a Serverless REST API in Minutes with the Serverless Framework](https://blog.codeship.com/a-serverless-rest-api-in-minutes/) - Most recent "getting started" post as of Jan 2016
- [Moving from Ruby on Rails to Serverless](http://microapps.com/blog/learnt-building-monolithic-rails-app/) - Blog post why and how this transition was made
- [Zerosharp blog posts series](http://blog.zerosharp.com/serverless-framework-part-1-up-and-running/) - Step-by-step development of an example application
- [Serverless and GraphQL](http://kevinold.com/2016/02/01/serverless-graphql.html) - How Serverless can be used with GraphQL
- [Serverless - The next big thing](https://www.linkedin.com/pulse/serverless-next-big-thing-colin-lyman) - Colin Lyman on Serverless as the next big thing
- [Building a website](http://zanon.io/posts/building-serverless-websites-on-aws-tutorial) - Tutorial on how to build a serverless website
- [Add CORS support](http://davidcai.github.io/blog/posts/serverless-and-cors/) - How you can add CORS support to your Serverless functions
- [AWS lambda framework "Serverless"](http://thenewstack.io/serverless-offers-framework-aws-lambda/) - Article about the Serverless framework
- [Using Python](https://serverlesscode.com/post/python-on-serverless-intro/) - Using Python with Serverless
- [Scheduled Lambda events](http://jamiecressey.com/2016/02/27/everyone-to-the-cloud/) - How to create scheduled Lambda events
- [Trek10 about Serverless](https://www.trek10.com/blog/serverless-framework-for-processes-projects-and-scale/) - A look at Serverless for processes, projects and scale
- [Serverless Slackbots](http://eng.localytics.com/serverless-slackbots-powered-by-aws/) - Slackbot implementation with Serverless
- [5 serverless computing frameworks to watch out for](http://www.forbes.com/sites/janakirammsv/2016/03/22/five-serverless-computing-frameworks-to-watch-out-for/#7a810ffc59d7) - Forbes blog post which compares five serverless frameworks

## Talks

- [JAWS @ re:Invent YouTube Video](https://www.youtube.com/watch?v=D_U6luQ6I90) - Presentation video of the re:Invent talk 
- [JAWS @ re:Invent presentation slides](http://de.slideshare.net/AmazonWebServices/dvo209-jaws-a-scalable-serverless-framework) - Presentation slides of the re:Invent talk
- [The dot Post](http://www.thedotpost.com/2015/12/nicolas-grenie-serverless-microservices-in-javascript) - The dot Post with a presentation about Serverless

## Amazon AWS resources

- [Amazon AWS homepage](http://aws.amazon.com) - Official Amazon AWS homepage
- [Free Amazon AWS tier](http://aws.amazon.com/free) - Highly recommended to get started with Amazon AWS
- [AWS S3](https://aws.amazon.com/s3) - File storage solution (used to server files such as HTML or JavaScript)
- [AWS Lambda](https://aws.amazon.com/lambda/details) - Details about the Lambda service
- [AWS Cloudformation](https://aws.amazon.com/cloudformation/) - Details about CloudFormation
- [AWS API Gateway](https://aws.amazon.com/api-gateway/) - Details about API Gateway
- [AWS IAM](https://aws.amazon.com/iam/) - Details about Identity and Access Management (IAM)
- [Cloudcraft](https://cloudcraft.co/) - Awesome tool to plan and visualize your AWS infrastructure

## Projects

- [React Serverless](https://github.com/hiromoon/react-serverless) - Use React together with Serverless
- [Serverless test plugin](https://github.com/arabold/serverless-test-plugin) - Test plugin
- [Serverless starter](https://github.com/serverless/serverless-starter) - Boilerplate for new projects
- [Lang Adventure backend](https://github.com/jonatasschagas/langadventurebackend) - Backend from Lang Adventure game
- [Serverless project written with ES2015](https://github.com/mpppk/serverless-project-written-in-es2015) - Project example written in ES2015
- [Serveress Telegram bot](https://github.com/minibikini/serverless-telegram-bot) - Telegram bot implementation
- [Serverless pre register](https://github.com/agentmilindu/Serverless-Pre-Register) - Product Pre-registration page
- [Serverless mapbox classic](https://github.com/LukeSwart/serverless-mapbox-classic) - API gateway that munges geojson coming from a mapbox classic editor
- [Universal Serverless React](https://github.com/jstrutz/universal-serverless-react) - React with Serverless
- [Serverless example](https://github.com/iblue/serverless-example) - Experimental example project
- [JAWS local server](https://github.com/martinlindenberg/JawsLocalServer) - Local server which let's you execute Lambda functions locally
- [DynamoDB CRUD example](https://github.com/jagthedrummer/serverlessDynamoCrudExample) - How to use DynamoDB with Serverless
- [GraphQL Blog](https://github.com/serverless/serverless-graphql-blog) - A Blog powered by GraphQL and Serverless
- [Password of the day](https://github.com/ZeroSharp/ServerlessPotd) - Password of the day service. Utilizing TypeScript
- [Shark Notes](https://github.com/JustServerless/shark-notes) - Full note taking tool (frontend and backend) which shows how to do CRUD with Serverless
- [func4](https://github.com/ac360/func4) - Show and create users
- [Boxify](https://github.com/jankei/boxify) - Boxify API service
- [MIDAAS API](https://github.com/presidential-innovation-fellows/midaas-api) - MIDAAS API
- [Zanon IO Demo](https://github.com/zanon-io/aws-serverless-demo) - https://github.com/zanon-io/aws-serverless-demo
- [Cortex](https://github.com/namastereid/cortex) - Cortex project
- [Protocol service](https://github.com/Backfeed/protocol-service) - Protocol service
- [Cat facts](https://github.com/ryansb/serverless-cat-facts) - Example how to use Serverless with Python
- [Notes](https://github.com/JustServerless/notes) - Note taking application written for the ["Learn Serverless"](http://learnserverless.club) book
- [Aquest](https://github.com/dherault/Aquest) - Demo application
- [Hello world](https://github.com/bart-blommaerts/serverless_helloworld) - Hello World application
- [Garage](https://github.com/bart-blommaerts/serverless_garage) - Managing cars
- [Slackbot scaffold](https://github.com/localytics/serverless-slackbot-scaffold) - Scaffold for a Serverless slackbot
- [Lambda-React-SSR](https://github.com/dherault/Lambda-React-SSR/) - Server-side rendering with React on Lambda
- [Authentication boilerplate](https://github.com/laardee/serverless-authentication-boilerplate) - Authentication boilerplate for Serverless

## Plugins

- [Plugin boilerplate](https://github.com/serverless/serverless-plugin-boilerplate) - Boilerplate code if you want to develop your own plugin
- [Serverless resources validation plugin](https://github.com/tmilewski/serverless-resources-validation-plugin) - Plugin which validates your CloudFormation template
- [Alerting](https://github.com/martinlindenberg/serverless-plugin-alerting) - Add Cloudwatch Alarms with SNS notifications
- [Lambda prune](https://github.com/Nopik/serverless-lambda-prune-plugin) - Automatically remove unused Lambda functions
- [Autoprune](https://github.com/kennu/serverless-plugin-autoprune) - Automatically remove unused Lambda functions
- [Swagger](https://github.com/marklawlor/serverless-swagger) - Swagger.io plugin
- [CORS](https://github.com/joostfarla/serverless-cors-plugin) - CORS plugin
- [Serve](https://github.com/Nopik/serverless-serve) - Test your lambda functionality locally
- [Base path plugin](https://github.com/daffinity/serverless-base-path-plugin) - Setting a base path for all API Gateway endpoints in a component
- [SNS](https://github.com/martinlindenberg/serverless-plugin-sns) - Plugin for SNS support
- [Cronjob](https://github.com/martinlindenberg/serverless-plugin-cronjob) - Plugin for Cronjobs
- [API Blueprint](https://github.com/hiroara/serverless-api-blueprint) - API documentation generator
- [VPC](https://github.com/martinlindenberg/serverless-plugin-vpc) - VPC support
- [Client S3](https://github.com/serverless/serverless-client-s3) - Handle static asset serving (like static frontends) via S3
- [Offline](https://github.com/dherault/serverless-offline) - An alternative to the Serve plugin, with Velocity templates support
- [Serverless optimizer plugin](https://github.com/asprouse/serverless-optimizer-plugin) - Fork of the optimizer plugin which uses Webpack
- [JSHint](https://github.com/joostfarla/serverless-jshint-plugin) - Detect errors and potential problems in your Lambda functions
- [Webpack](https://github.com/asprouse/serverless-webpack-plugin) - Use Webpack to optimize your Serverless Node.js Functions
- [Runtime Babel](https://github.com/serverless/serverless-runtime-babel) - Babel runtime for the Serverless framework (so that ES6 and ES7 syntax can be used)
- [https://github.com/marclar/serverless-runtime-streamline](https://github.com/marclar/serverless-runtime-streamline) - Streamline.js for Serverless

## Modules

- [NPM registry](https://github.com/Inbot/awsm-npm-registry) - NPM registry
- [Users](https://github.com/dekz/awsm-users) - AWSM module for authentication
- [Test AWS users library](https://github.com/oren/test-awsm-users) - Test AWSM users
- [Stripe webhook](https://github.com/eahefnawy/serverless-stripe-webhook) - Webhook for Stripe payments
- [Slack webhook](https://github.com/eahefnawy/serverless-slack-webhook) - Webhook for Slack
- [Slack](https://github.com/serverless/serverless-slack) - Slack boilerplate functionality
- [Examples](https://github.com/remicastaing/serverless-examples) - Module with example functions
- [Slackbot](https://github.com/serverless/serverless-slackbot) - Module to create your own slackbot
- [Images](https://github.com/awsm-org/awsm-images) - Image modifications
- [Cloudfront](https://github.com/boushley/awsm-cloudfront) - Puts CloudFront distribution in front of your project
- [S3 token vendor](https://github.com/binoculars/awsm-s3tokenvendor) - Return upload tokens for S3 objects
- [Loggly](https://github.com/jwulf/awsm-loggly) - Provide logging to your lambdas
- [Middleware](https://github.com/jwulf/awsm-middleware) - Middleware for your project
- [GitHub Webhook](https://github.com/bisque33/awsm-github-webhook) - GitHub webhook support
- [Comments](https://github.com/donleyp/awsm-comments) - Implements comments using DynamoDB
- [3scale](https://github.com/jerzyn/awsm-3scale) - Integrates 3scale API management platform

## Literature

- [Serverless - By Obie Fernandez](https://leanpub.com/serverless) - Book about Serverless development (also covers usage of the Serverless framework)
- [Learn Serverless - By Philipp Müns](http://learnserverless.club) - Book focused on the serverless.com framework

## Professional services
- [Just Serverless](http://www.justserverless.com) - Serverless specialized agency
- [Trek10](http://trek10.com) - Consultancy
- [Parallax](https://parall.ax/) - Consultancy
- [SC5 Online](https://sc5.io) - Serverless agency
- [Carrot creative](https://carrot.is) - Agency
- [Microapps](http://microapps.com) - Agency
- [Apiwise](http://www.apiwise.nl) - Agency
