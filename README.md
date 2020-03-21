# :fire: power-of-the-serverless
Serverless actually a new way to pay for and work with servers that, in many cases, is cheaper and easier than buying and managing your own servers. Front-end developers! Here's one way to think about it: server-less allow you to take your front-end skills and do things that typically only a back-end can do. Here are remarkable compiled server-less services that can make possible to do things only a backend can do. 

Web developers of all kinds can take advantage of it, but this is particularly interested in how it relates to and helps front-end web developers.


- [Contents](#contents)

  - [Serverless Providers](#providers)
  - [Auth](#auth)
  - [CMS](#cms)
  - [Email/SMS/Notifications](#email/sms/notificatios)
  - [Forms](#forms)
  - [Media-Storage](#media-storage)
  - [Monitoring](#monitoring)
  - [Payments](#payments)
  - [Real Time](#real-time)
  - [Search](#kenya)
  - [Static-File-Hosting](#static-file-hosting)
  

If you're la serverless noob and want to learn any of this resources, or you're thinking of learning some you don't know, I've compiled some resources to help you with that: [RESOURCES](/RESOURCES.md)

<!-- Serverless Providers below-->

### Serverless Providers
Major Serverless providers

#### Backendless

- [Backendless](https://backendless.com/)

##### Capabilities
Authentication,
Real-time database

##### Overview
All-in-one kind of service similar to Firebase, including the realtime database. Has a PRO version you can host yourself, if you're, ya know, into running servers.


#### Microsoft Azure

- [Microsoft Azure](https://azure.microsoft.com/en-us/)

##### Capabilities
Provides everything

##### Overview
A major infrastructure provider with solutions for about just everything, and generally considered the cheapest. For working with cloud functions, there is an online editor, but it also allows GitHub sync.


#### Amazon Web Service

- [Amazon Web Service](https://aws.amazon.com/)

##### Capabilities
Provides everything

##### Overview
Lambda, API Gateway, S3, and Cognito (auth) are probably the most relevant things to front-end developers.


#### Google Cloud Platform

- [Google Cloud Platform](https://cloud.google.com/)

##### Capabilities
Provides everything

##### Overview
More of a major infastructure provider in vein of Amazon Web Services than a toolkit for building out an app like Firebase is.


#### Google Firebase

- [Google Firebase](https://firebase.google.com/)

##### Capabilities
Authentication,
Real-time database,
Cloud functions,
Media Storage

##### Overview
Google Firebase is very powerful while being very easy to use. For example, you can run cloud functions, but you don't even need to for most data storage and retrieval or auth. It might be expensive to scale on though.


#### IBM Cloud Functions

- [IBM Cloud Functions](https://cloud.ibm.com/functions/)

##### Capabilities
Cloud Functions

##### Overview
Run your application code without servers, scale it automatically, and pay nothing when it's not in use.


#### Webtask

- [Webtask](https://webtask.io/)

##### Capabilities
Authentication,
Real-time database

##### Overview
An in-browser editor for creating and testing cloud functions. Seems like the nicest experience for this particular job. It's kinda of an elaborate demonstration of Auth0 Extend, which is essentially a way to take Webtask and put it in your own app.


#### StdLib

- [StdLib](https://stdlib.com/)

##### Capabilities
Cloud Functions

##### Overview
StdLib is based on Function as a Service ("server-less") architecture, popularized by AWS Lambda. You can use StdLib to build modular, scalable APIs for yourself and other developers in minutes without having to manage servers, gateways, domains, write documentation, or build SDKs. They also offer an online code editor for working with the APIs.


<!-- Auth below-->

### Auth
For sites that have users or administrators that need to log in to do things, OAuth services are there to help

#### AuthO

- [AuthO](https://auth0.com/)

##### Capabilities
Authentication

##### Overview
Helps you in handling your own site's authentication system or integrates with loads of other services.


#### Okta

- [Okta](https://developer.okta.com/)

##### Capabilities
Authentication

##### Overview
An SDK that helps you to handle all auth and user management

#### Google Firebase

- [Okta](https://firebase.google.com/)

##### Capabilities
Authentication,
Media Storage,
Cloud Functions
RealTime Database

##### Overview
You don't need any cloud functions, it helps you handles authentication entirely from the frontend.

#### Netlify Identity

- [Netlify Identity](https://docs.netlify.com/visitor-access/identity/)

##### Capabilities
Authentication,
Hosting

##### Overview
Backed by the GoTrue API, Netlify Identity service brings a full suite of authentication functionality.



<!-- CMS below-->

### CMS
You want to abstract UI and auth for managing content away into a service, and access the content via an API, CMS services are there to help.

#### Sanity

- [Sanity](https://www.sanity.io/)

##### Capabilities
CMS

##### Overview
You can edit collaboratively, distribute over APIs and freely decide later how and where your content will be used.

#### Shifter

- [Shifter](https://www.getshifter.io/)

##### Capabilities
CMS,
WordPress

##### Overview
WordPress sites automatically have a Rest API. But you still need to host the site somewhere and serverless isn't really gonna happen. Except... Shifter is the WordPress hosting solution that combines static site generation and serverless architecture with the world’s most popular CMS.


#### DatoCMS

- [DatoCMS](https://www.datocms.com/)

##### Capabilities
CMS

##### Overview
Hosted CMS that outputs all your data as a JSON API.


#### Flamelink

- [Flamelink](https://flamelink.io/)

##### Capabilities
CMS,
Firebase

##### Overview
A Realtime Headless CMS for Firebase


#### Better CMS

- [Better CMS](https://buttercms.com/)

##### Capabilities
CMS

##### Overview
A UI (and API) for managing/creating content, and APIs/SDKs for getting out your content.


#### Prismic

- [Prismic](https://prismic.io/)

##### Capabilities
CMS

##### Overview
A UI (and API) for managing/creating content, and APIs/SDKs for getting out your content.


#### Contentful

- [Contentful](https://www.contentful.com/)

##### Capabilities
CMS

##### Overview
A UI (and API) for managing/creating content, and APIs/SDKs for getting out your content.


#### Netlify CMS

- [Netlify CMS](https://www.netlifycms.org/)

##### Capabilities
Hosting,
CDN,
CMS

##### Overview
This is a React SPA that works with any static site generator.



<!-- Email/SMS/Notifications below-->

### Email/SMS/Notifications
Email, SMS and notification services of any kind

#### Twilio

- [Twilio](https://www.twilio.com/)

##### Capabilities
SMS,
Push Notification,
Voice,
WebRTC

##### Overview
Twilio offers powerful APIs for text messaging, voice, and video.


#### Mailgun

- [Mailgun](https://www.mailgun.com/)

##### Capabilities
Email

##### Overview
Email sending service.


#### EmailJS

- [EmailJS](https://www.emailjs.com/)

##### Capabilities
Email

##### Overview
You don't need any server side code at all for this.


#### PopcornNotify

- [PopcornNotify](https://popcornnotify.com/)

##### Capabilities
Email,
SMS

##### Overview
Email and text messages with just one javaScript API.


#### OneSignal

- [OneSignal](https://onesignal.com/)

##### Capabilities
Push Notifications

##### Overview
Android, iOS, and Web push notifications


#### Sendgrid

- [Sendgrid](https://sendgrid.com/)

##### Capabilities
Email

##### Overview
Email sending service, and an email builder tool as well.


#### Sparkpost

- [Sparkpost](https://www.sparkpost.com/)

##### Capabilities
Email

##### Overview
Email sending service, and comes with analytics too.



<!-- Forms below-->

### Forms
Form builder apps. You can host the form and embed with an iframe, or you can host the form and point the submission to them.

#### Google Forms

- [Google Forms](https://www.google.com/forms/about/)

##### Capabilities
Forms

##### Overview
An easy and free service


#### Wufoo

- [Wufoo](https://www.wufoo.com/)

##### Capabilities
Forms

##### Overview
Build custom online forms that you can use to collect data, payments and to automate your workflows.
Secure forms. API access to data. Reporting. Logic & Branching. Integrations.


#### Formstack

- [Formstack](https://www.formstack.com/)

##### Capabilities
Forms

##### Overview
Payments. Integrations


#### TypeForm

- [TypeForm](https://www.typeform.com/)

##### Capabilities
Forms

##### Overview
Forms with a novel UI/UX where each question is essentially a full page view that slides by.


#### PageClip

- [PageClip](https://pageclip.co/)

##### Capabilities
Forms

##### Overview
Collect info from users without a server—Pageclip is your server. Lead capture forms, surveys, newsletter forms, contact forms, etc. Setup any form in seconds.
Point the `action` attribute at a pageclip URL and it saves all the data for you. It can trigger an email notification, or makes the data available as JSON or CSV.


#### Formspree

- [Formspree](https://formspree.io/)

##### Capabilities
Forms

##### Overview
You point `action` attribute like many of the other services, but the hook here is that you use your own email address in the URL, so you don't even have to register.


#### Formkeep

- [Formkeep](https://formkeep.com/)

##### Capabilities
Forms

##### Overview
Point the `action` attribute at Formkeep and it'll handle the form processing for you. Integrates with services like Zapier, MailChimp, Slack, and Trello. Notable features include spam filtering and auto responders.


#### Formaholic

- [Formaholic](https://formaholic.com/)

##### Capabilities
Forms

##### Overview
Their tagline: Send your form to our URL and we'll save it & send it to your email. No server side code required - perfect for static sites!


#### Basin

- [Basin](https://usebasin.com/)

##### Capabilities
Forms

##### Overview
Point the `action` attribute at Basin and it'll handle the form processing for you. Basin features include Zapier integration (which connects to loads of other services), spam filtering, response emails, file uploads, and more.


#### Jotform

- [Jotform](https://www.jotform.com/)

##### Capabilities
Forms

##### Overview
Has a drag and drop form builder.


#### Formcarry

- [Formcarry](https://formcarry.com/)

##### Capabilities
Forms

##### Overview
Point the `action` attribute at Formcarry and it'll handle the form processing for you. Notably, it has integrations with services like Zapier, Salesforce, Intercom, and Slack. It also has Web-hooks to notify other services (which is nice for serverless architectures).


<!-- Media storage below-->

### Media storage
Whether your website is using Serverless or not, you can use this services to manage and manipulate your media files.

#### Cloudinary

- [Cloudinary](https://cloudinary.com/)

##### Capabilities
Images,
Video

##### Overview
Cloudinary does fancy image/video stuff like manipulation and optimization, but will also directly host for you, making it a good Serverless fit.


#### Kloudless

- [Kloudless](https://kloudless.com/)

##### Capabilities
File Storage

##### Overview
Integrates multiple file storage solutions with one API.


#### Uploadcare

- [Uploadcare](https://uploadcare.com/)

##### Capabilities
File Storage

##### Overview
Full featured file uploader and file storage.


#### Filestack

- [Filestack](https://www.filestack.com/)

##### Capabilities
File Storage

##### Overview
Offers an all-JavaScript file picker that integrates with other services. The host the uploaded files.


#### Amazon S3

- [Amazon S3](https://aws.amazon.com/s3/)

##### Capabilities
File Storage

##### Overview
Object storage built to store and retrieve any amount of data from anywhere



<!-- Monitoring below-->

### Monitoring
Services in which you can install to monitor your server. When you're working serverless land, you may need/want a service that can work without you installing things onto a server. Here are some of those services that can help you monitor your serverless apps.


#### Dashbird

- [Dashbird](https://dashbird.io/)

##### Capabilities
Monitoring

##### Overview
Their tagline: AWS Lambda monitoring, alerting and debugging made easy. 2-min setup, no code changes!


#### Thundra

- [Thundra](https://www.thundra.io/)

##### Capabilities
Monitoring

##### Overview
Their tagline: Full observability for AWS Lambda. Instrument and profile your functions with zero overhead. Gain visibility to identify and resolve issues faster.


#### IOpipe

- [IOpipe](https://newrelic.com/products/serverless-aws-lambda?utm_source=iopipe?source=iopipe)

##### Capabilities
Monitoring

##### Overview
IOpipe is a tool and service that helps you instrument and monitor your functions in dev and production. Free tier available for smaller projects.


<!-- Payment below-->

### Payment
Processing payments is sensitive stuff, but modern providers has done a lot to largely abstract that difficulty away.


#### Stripe

- [Stripe](https://stripe.com/checkout)

##### Capabilities
Payments

##### Overview
Probably the most beloved payment service out there. There are payment services built on top of Stripe to make it easier, like Plasso.


#### Paystack

- [Paystack](https://paystack.com/)

##### Capabilities
Payments

##### Overview
Probably the second most beloved payment service out there. Paystack helps businesses in Africa get paid by anyone, anywhere in the world


#### Paypal

- [Paypal](https://developer.paypal.com/docs/paypal-payments-standard/integration-guide/buy-now-step-1/)

##### Capabilities
Payments

##### Overview
The most relevant PayPal service is probably their Buy Now buttons, which send buyers to PayPal to check out, and then back to the website.


#### Braintree

- [Braintree](https://www.braintreepayments.com/)

##### Capabilities
Payments

##### Overview
Braintree is owned by PayPal, so it is the one other payment service that can take PayPal. The appeal of Braintree is that it makes taking multiple forms of payments (e.g. credit cards and PayPal and Apple Pay, for example) much easier, and through just one set of APIs.



<!-- Real Time below-->

### Real Time
Imagine things like building your own chat or your own dashboards that update to new data without needing to be refreshed. Yeah these are the services that you can consider.

#### Pusher

- [Pusher](https://pusher.com/)

##### Capabilities
Realtime

##### Overview
Realtime APIs


#### Google Firebase

- [Google Firebase](https://firebase.google.com/)

##### Capabilities
Authentication,
Media Storage,
Cloud Functions,
Realtime Database

##### Overview
The realtime database is very fast and ready to be used for realtime features. 


#### PubNub

- [PubNub](https://www.pubnub.com/)

##### Capabilities
Realtime

##### Overview
Realtime APIs


<!-- Search below-->

### Search
People love your website, but going through all that content to find what they are looking for can take a long time, thinking about that? To make a great website even better, simple, custom search services can help you do that, below are these services:

#### Google Custom Search Engine

- [Google Custom Search Engine](https://cse.google.com/about)

##### Capabilities
Search

##### Overview
With Google Custom Search, add a search box to your homepage to help people find what they need on your website.
You create mini search engines that are scoped by URL and can then embed them onto your own site.


#### Agolia

- [Agolia](https://www.algolia.com/)

##### Capabilities
Search

##### Overview
Algolia’s search-as-a-service and full suite of APIs allow teams to easily develop
tailored, fast Search and Discovery experiences that delight and convert.
Put all your searchable data in Algolia, and you and query and get results through APIs incredibly fast.


<!-- Static file hosting below-->

### Static file hosting
Although any host can serve up static assets. But these hosts specialize in it.

#### Github Pages

- [Github Pages](https://pages.github.com/)

##### Capabilities
Hosting,
Git

##### Overview
Make any repository, a website


#### Amazon S3

- [Amazon S3](https://aws.amazon.com/s3/)

##### Capabilities
Hosting

##### Overview
S3 is normally mostly used for media files, but you can use a bucket as a website. Take a look at [Up](https://apex.sh/docs/up/) to help with deploying serverless apps to it.


#### Netlify

- [Netlify](https://www.netlify.com/)

##### Capabilities
Hosting,
CDN,
Cloud Functions,
Git

##### Overview
Netlify offers essentially very fancy static file hosting. They have many bonus features like form handling and a CLI. 


#### Codepen

- [Codepen](https://codepen.io/pro/projects/)

##### Capabilities
Hosting,
Code Editor,
File Storage,
Preprocessing,

##### Overview
Zero setup, full-featured front end web development environment, right here in your web browser.
The one and only. Pens are great for quick demos with bits of HTML, CSS, and JavaScript. CodePen Projects gives you a complete file system of your own.


#### ZEIT

- [ZEIT](https://zeit.co/)

##### Capabilities
Hosting

##### Overview
This is the fastest of all. A command-line based deployment tool for any framework. Deploy an app with just one command.


#### Surge

- [Surge](https://surge.sh/)

##### Capabilities
Hosting

##### Overview
A command-line based deployment tool for any framework.


#### Aerobatic

- [Aerobatic](https://www.aerobatic.com/)

##### Capabilities
Hosting,

##### Overview
Blazing fast performance on our highly tuned, purpose-built CDN. Expand the possibilities of static sites with plugins.
Built for static sites, but extensible through "plugins" for stuff like redirects and form submissions.


#### Firebase Hosting

- [Firebase Hosting](https://firebase.google.com/docs/hosting/)

##### Capabilities
Hosting,

##### Overview
Firebase Hosting is production-grade web content hosting for developers. With Hosting, you can quickly and easily deploy web apps and static content to a global content delivery network (CDN) with a single command.


Want to contribute? [CONTRIBUTE](/CONTRIBUTE.md)

Star the repo if you find it helpful, fork if you want and happy building!!

My love :love: to the community