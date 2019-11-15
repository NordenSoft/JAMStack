# <span style="color:#00c7b7"> Welcome to JAMStack Expert Pages

When we talk about “The Stack,” we no longer talk about operating systems, specific web servers, backend programming languages, or databases.

The JAMstack is not about specific technologies. It’s a new way of building websites and apps that delivers better performance, higher security, lower cost of scaling, and a better developer experience.

# What is the JAMStack?

You may have already seen or worked on a JAMstack site! They do not have to include all attributes of JavaScript, APIs, and Markup. They might be built using by hand, or with Jekyll, Hugo, Nuxt, Next, Gatsby, or another static site generator...

The thing that they all have in common is that they don’t depend on a web server.

### JavaScript
Any dynamic programming during the request/response cycle is handled by JavaScript, running entirely on the client. This could be any frontend framework, library, or even vanilla JavaScript.

### APIs
All server-side processes or database actions are abstracted into reusable APIs, accessed over HTTPS with JavaScript. These can be custom-built or leverage third-party services.

### Markup
Templated markup should be prebuilt at deploy time, usually using a site generator for content sites, or a build tool for web apps.

# <span style="color:#00c7b7"> Why the JAMstack?


## Better Performance

Why wait for pages to build on the fly when you can generate them at deploy time? When it comes to minimizing the time to first byte, nothing beats pre-built files served over a CDN.

## Higher Security

With server-side processes abstracted into microservice APIs, surface areas for attacks are reduced. You can also leverage the domain expertise of specialist third-party services.

## Cheaper, Easier Scaling

When your deployment amounts to a stack of files that can be served anywhere, scaling is a matter of serving those files in more places. CDNs are perfect for this, and often include scaling in all of their plans.

## Better Developer Experience

Loose coupling and separation of controls allow for more targeted development and debugging, and the expanding selection of CMS options for site generators remove the need to maintain a separate stack for content and marketing.

# <span style="color:#00c7b7"> Technologies we use

### <span style="color:#3e70b1"> Auth0

#### Auth0 Overview

Auth0 provides authentication and authorization as a service.

We are here to give developers and companies the building blocks they need to secure their applications without having to become security experts.

You can connect any application (written in any language or on any stack) to Auth0 and define the identity providers you want to use (how you want your users to log in).

Based on your app's technology, choose one of our SDKs (or call our API), and hook it up to your app. Now each time a user tries to authenticate, Auth0 will verify their identity and send the required information back to your app.

#### Why use Auth0?

Take a look at just a few of Auth0's use cases:

  - You built an awesome app and you want to add user authentication and authorization. Your users should be able to log in either with username/password or with their social accounts (such as Facebook or Twitter). You want to retrieve the user's profile after the login so you can customize the UI and apply your authorization policies.
  - You built an API and you want to secure it with OAuth 2.0.
  - You have more than one app, and you want to implement Single Sign-on (SSO).
  - You built a JavaScript front-end app and a mobile app, and you want them both to securely access your API.
  - You have a web app which needs to authenticate users using Security Assertion Markup Language (SAML).
  - You believe passwords are broken and you want your users to log in with one-time codes delivered by email or SMS.
  - If one of your user's email addresses is compromised in some site's public data breach, you want to be notified, and you want to notify the users and/or block them from logging in to your app until they reset their password.
  - You want to act proactively to block suspicious IP addresses if they make consecutive failed login attempts, in order to avoid DDoS attacks.
  - You are part of a large organization who wants to federate their existing enterprise directory service to allow employees to log in to the various internal and third-party applications using their existing enterprise credentials.
  - You don't want (or you don't know how) to implement your own user management solution. Password resets, creating, provisioning, blocking, and deleting users, and the UI to manage all these. You just want to focus on your app.
  - You want to enforce multi-factor authentication (MFA) when your users want to access sensitive data.
  - You are looking for an identity solution that will help you stay on top of the constantly growing compliance requirements of SOC2, GDPR, PCI DSS, HIPAA, and others.
  - You want to use analytics to track users on your site or application. You plan on using this data to create funnels, measure user retention, and improve your sign-up flow.
  
### <span style="color:#3e70b1"> Azure Functions

#### Azure Functions
Azure Functions is an event driven, compute-on-demand experience that extends the existing Azure application platform with capabilities to implement code triggered by events occurring in virtually any Azure or 3rd party service as well as on-premises systems. Azure Functions allows developers to take action by connecting to data sources or messaging solutions, thus making it easy to process and react to events. Azure Functions scale based on demand and you pay only for the resources you consume.

This repository acts as a directory for folks looking for the various resources we have for Azure Functions.

#### Get Started with Azure Functions
To get started with Azure Functions, you can visit (functions.azure.com) and click on the green Get Started button. If you need a trial Azure subscription, there is also a link on that page.

### <span style="color:#3e70b1"> Bootstrap
Build responsive, mobile-first projects on the web with the world’s most popular front-end component library.

Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. Quickly prototype your ideas or build your entire app with our Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery.

## Headless CMS
  
### <span style="color:#3e70b1"> Contentful
Contentful helps the world's leading brands manage content across their digital products and channels. We offer a content layer for enterprises to unify their content in a single hub — no more content stuck in CMS silos. We help you structure that content so it can be reused across digital properties, with an endlessly extensible framework for integrating with hundreds of leading-edge tools.

In 2013, Sascha Konietzke and Paolo Negri launched Contentful as a solution to the problems caused by legacy CMSes. They pioneered a new software category for professional developers to make content programmable for any digital channel.

While CMSes were created to build web pages, Contentful is built for the fast-moving, omnichannel world.

Today, Contentful is the headless CMS market leader, serving thousands of leading global brands and empowering more than 400,000 users.
  
### <span style="color:#3e70b1"> Firebase
Whether you are considering Google Firebase or among the nearly half-million developers already using it, this course is designed for you. Google Firebase offers a set of features to help you maximize your app development efforts. In this first look, Joe Marini takes you on a tour of the features that support Android app development. Joe begins with an overview, then dives into three core areas: Firebase Analytics, Firebase Remote Config, and Firebase Authentication. He demonstrates how to create your own project, add APIs, configure parameters and conditions, and implement email and password authentication. He wraps up by visiting the Firebase console where you can evaluate users, engagement metrics, and earnings.

- Creating a Firebase project
- Adding Firebase Analytics
- Using the analytics API
- Incorporating Firebase Remote Config
- Configuring parameters and conditions
- Implementing email and password authentication
- Viewing users in the Firebase console
  
### <span style="color:#3e70b1"> Gatsby
Gatsby is a React-based, GraphQL powered, static site generator. What does that even mean?  Well, it weaves together the best parts of React, webpack, react-router, GraphQL, and other front-end tools in to one very enjoyable developer experience. Don’t get hung up on the moniker ‘static site generator’.  That term has been around for a while, but Gatsby is far more like a modern front-end framework than a static site generator of old.

It uses powerful preconfiguration to build a website that uses only static files for incredibly fast page loads, service workers, code splitting, server-side rendering, intelligent image loading, asset optimization, and data prefetching. All out of the box. I didn’t believe the speed until I tried it myself.

You code and develop your site, Gatsby transforms it into a directory with a single HTML file and your static assets. This folder is uploaded to your favorite hosting provider, and voila.
Overall think, part Jekyll, part create-react-app.

2:  What makes Gatsby special?

You may be thinking, “I have a nice web pack config I use”, or “create-react-app works for me”, or "Jekyll is fine for my blog.”  Well, I think there are three things that make Gatsby very special versus these other tools.

First, is the way Gatsby uses GraphQL to build it’s data layer.  What do I mean by that?  Gatsby is made to collect your data from wherever it may be: Markdown, JSON, your favorite CMS, third party APIs, anywhere! And at build time, it creates an internal GraphQL server of all of this data. So in your react components, all of your data is queried at build time from that same place, in the same way through GraphQL.

The second reason it’s special is the richness of the Gatsby ecosystem. Gatsby has not been around for too long, but already boasts great documentation, and a number of starters to help you get a site up quickly.  That GraphQL data collection I mentioned before may sound intimidating, but due to Gatsby's well-documented data source plugins, it can be as simple as a few lines of code in the config file.

Lastly, is its dedication to performance. Every aspect of performance and accessibility is a point of emphasis, and you can really feel that in the final product.  More so than any boilerplate or generator I have come across, Gatsby lives up to the hype.

3:  Do I have to know React and GraphQL?

One of the biggest hurdles to someone trying out Gatsby is saying, “Well, I don’t know GraphQL”, or “I don’t know React and I really don’t have the time or energy to learn those just so I can try Gatsby.”  Fair enough, and as someone who knew React, but was intimidated by GraphQL, I put off learning Gatsby for way too long after first hearing about it.  But, I can confidently say that if you only know one or don’t know either of React and GraphQL, Gatsby is actually a great point of entry.  It has fantastic documentation and examples of React and GraphQL, and its structure lends itself to ‘thinking in React’ and ‘thinking in GraphQL’.

Now, as far as, can you use Gatsby without these?  I actually tried it.  As I mentioned, I knew React, but not GraphQL, and thought, I’ll just not use the GraphQL part, you know just make regular API calls in my components, etc.  Don’t do this.  It misses the purpose of Gatsby entirely, and hamstrings you completely.  Kind of like saying, “Can I use React without JSX?”

So, yes, React and GraphQL are crucial for Gatsby, but if you don’t know them, Gatsby is an excellent tool to learn them, and not an excuse not to.

4: How do I get started?
If you’re thinking about getting started, as I have mentioned before, Gatsby has excellent documentation and tutorials, so head over to gatsbyjs.org and follow along:

          1. Click on docs and follow the instructions there.
          2. Install the global Gatsby CLI.
          3. Run the Gatsby `new` command with the name of your site. `cd` in to the new directory.
          4. Run ‘gatsby develop’ and click on the `localhost` link in your console.

And there we go, our Gatsby site is up and running.  To compile this for production, we would stop the `develop` and run `gatsby build`. And there you can see the `build` folder meant to be uploaded to your hosting provider.

Gatsby also includes the idea of ‘starters’. Starters are something like boilerplate and templates for Gatsby.  If you know your data will be coming from a certain source, or your site will function in a certain way, such as a blog, there is probably a starter that has the data sources preconfigured, and also the styling and component structure will be setup and opinionated.  This makes getting up and running very quick and easy.

If there is not a starter that fits you, you can use Gatsby’s default starter, and find your data source plugin and follow its install instructions. I would recommend starting with the Gatsby default starter tutorial to get going, and I think you’ll be surprised how quickly you feel comfortable and itching to hook it up to your data or favorite CMS.

5: Whats the future of Gatsby?
Gatsby has not been around too long.  Its version 1 was released in July 2017.  Since then, its use has grown tremendously, and version 2 beta was released in June 2018.  There will be a few technical changes to Gatsby, plus what I believe will be a general outlook shift for Gatsby.  Some of the technical updates of Gatsby v2 are: 

An upgrade to webpack 4 from webpack 1, which should lead to some serious performance gains, especially during the build step.
Adoption of Reach Router, a project similar to react-router, but built with accessibility of single page apps in mind.
Some tweaks to where you can use GraphQL in Gatsby, from being limited to Gatsby’s very top level React components, to now being able to define a query in any component.

Upgrade React to v16, so you can use Context, Fragments, and any other aspect of the latest version of React.
  
### <span style="color:#3e70b1"> Git
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Github
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> GitHub API
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Github Pages
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Google Analytics
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Jekyll
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Netlify
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.### <span style="color:#fbc993"> Netlify CMS

### <span style="color:#3e70b1"> React
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> React-Static
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Sanity.io
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Sass
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Serverless DB
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Service Workers
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Vanilla JS & CSS
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Web App Manifest
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Webpack
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  

----

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/NordenSoft/JAMStack/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

