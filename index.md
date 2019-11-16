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

With server-side processes abstracted into microservice APIs, surface areas for attacks are reduced. You can also leverage the domain expertise of specialist third-party services..

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

And there we go, our Gatsby site is up and running.  To compile this for production, we would stop the 'develop' and run 'gatsby build'. And there you can see the `build` folder meant to be uploaded to your hosting provider.

Gatsby also includes the idea of ‘starters’. Starters are something like boilerplate and templates for Gatsby.  If you know your data will be coming from a certain source, or your site will function in a certain way, such as a blog, there is probably a starter that has the data sources preconfigured, and also the styling and component structure will be setup and opinionated.  This makes getting up and running very quick and easy.

If there is not a starter that fits you, you can use Gatsby’s default starter, and find your data source plugin and follow its install instructions. I would recommend starting with the Gatsby default starter tutorial to get going, and I think you’ll be surprised how quickly you feel comfortable and itching to hook it up to your data or favorite CMS.

5: Whats the future of Gatsby?
Gatsby has not been around too long.  Its version 1 was released in July 2017.  Since then, its use has grown tremendously, and version 2 beta was released in June 2018.  There will be a few technical changes to Gatsby, plus what I believe will be a general outlook shift for Gatsby.  Some of the technical updates of Gatsby v2 are: 

An upgrade to webpack 4 from webpack 1, which should lead to some serious performance gains, especially during the build step.
Adoption of Reach Router, a project similar to react-router, but built with accessibility of single page apps in mind.
Some tweaks to where you can use GraphQL in Gatsby, from being limited to Gatsby’s very top level React components, to now being able to define a query in any component.

Upgrade React to v16, so you can use Context, Fragments, and any other aspect of the latest version of React.
  
### <span style="color:#3e70b1"> Git
By far, the most widely used modern version control system in the world today is Git. Git is a mature, actively maintained open source project originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel. A staggering number of software projects rely on Git for version control, including commercial projects as well as open source. Developers who have worked with Git are well represented in the pool of available software development talent and it works well on a wide range of operating systems and IDEs (Integrated Development Environments).

Having a distributed architecture, Git is an example of a DVCS (hence Distributed Version Control System). Rather than have only one single place for the full version history of the software as is common in once-popular version control systems like CVS or Subversion (also known as SVN), in Git, every developer's working copy of the code is also a repository that can contain the full history of all changes.

In addition to being distributed, Git has been designed with performance, security and flexibility in mind.

Performance
The raw performance characteristics of Git are very strong when compared to many alternatives. Committing new changes, branching, merging and comparing past versions are all optimized for performance. The algorithms implemented inside Git take advantage of deep knowledge about common attributes of real source code file trees, how they are usually modified over time and what the access patterns are.

Unlike some version control software, Git is not fooled by the names of the files when determining what the storage and version history of the file tree should be, instead, Git focuses on the file content itself. After all, source code files are frequently renamed, split, and rearranged. The object format of Git's repository files uses a combination of delta encoding (storing content differences), compression and explicitly stores directory contents and version metadata objects.

Being distributed enables significant performance benefits as well.

For example, say a developer, Alice, makes changes to source code, adding a feature for the upcoming 2.0 release, then commits those changes with descriptive messages. She then works on a second feature and commits those changes too. Naturally these are stored as separate pieces of work in the version history. Alice then switches to the version 1.3 branch of the same software to fix a bug that affects only that older version. The purpose of this is to enable Alice's team to ship a bug fix release, version 1.3.1, before version 2.0 is ready. Alice can then return to the 2.0 branch to continue working on new features for 2.0 and all of this can occur without any network access and is therefore fast and reliable. She could even do it on an airplane. When she is ready to send all of the individually committed changes to the remote repository, Alice can "push" them in one command.

Security
Git has been designed with the integrity of managed source code as a top priority. The content of the files as well as the true relationships between files and directories, versions, tags and commits, all of these objects in the Git repository are secured with a cryptographically secure hashing algorithm called SHA1. This protects the code and the change history against both accidental and malicious change and ensures that the history is fully traceable.

With Git, you can be sure you have an authentic content history of your source code.

Some other version control systems have no protections against secret alteration at a later date. This can be a serious information security vulnerability for any organization that relies on software development.

Flexibility
One of Git's key design objectives is flexibility. Git is flexible in several respects: in support for various kinds of nonlinear development workflows, in its efficiency in both small and large projects and in its compatibility with many existing systems and protocols.

Git has been designed to support branching and tagging as first-class citizens (unlike SVN) and operations that affect branches and tags (such as merging or reverting) are also stored as part of the change history. Not all version control systems feature this level of tracking.

Version control with Git
Git is the best choice for most software teams today. While every team is different and should do their own analysis, here are the main reasons why version control with Git is preferred over alternatives:

Git is good
Git has the functionality, performance, security and flexibility that most teams and individual developers need. These attributes of Git are detailed above. In side-by-side comparisons with most other alternatives, many teams find that Git is very favorable.

Git is a de facto standard
Git is the most broadly adopted tool of its kind. This is makes Git attractive for the following reasons. At Atlassian, nearly all of our project source code is managed in Git.

Vast numbers of developers already have Git experience and a significant proportion of college graduates may have experience with only Git. While some organizations may need to climb the learning curve when migrating to Git from another version control system, many of their existing and future developers do not need to be trained on Git.

In addition to the benefits of a large talent pool, the predominance of Git also means that many third party software tools and services are already integrated with Git including IDEs, and our own tools like DVCS desktop client Sourcetree, issue and project tracking software, Jira, and code hosting service, Bitbucket.

If you are an inexperienced developer wanting to build up valuable skills in software development tools, when it comes to version control, Git should be on your list.

Git is a quality open source project
Git is a very well supported open source project with over a decade of solid stewardship. The project maintainers have shown balanced judgment and a mature approach to meeting the long term needs of its users with regular releases that improve usability and functionality. The quality of the open source software is easily scrutinized and countless businesses rely heavily on that quality.

Git enjoys great community support and a vast user base. Documentation is excellent and plentiful, including books, tutorials and dedicated web sites. There are also podcasts and video tutorials.

Being open source lowers the cost for hobbyist developers as they can use Git without paying a fee. For use in open-source projects, Git is undoubtedly the successor to the previous generations of successful open source version control systems, SVN and CVS.

Criticism of Git
One common criticism of Git is that it can be difficult to learn. Some of the terminology in Git will be novel to newcomers and for users of other systems, the Git terminology may be different, for example, revert in Git has a different meaning than in SVN or CVS. Nevertheless, Git is very capable and provides a lot of power to its users. Learning to use that power can take some time, however once it has been learned, that power can be used by the team to increase their development speed.

For those teams coming from a non-distributed VCS, having a central repository may seem like a good thing that they don't want to lose. However, while Git has been designed as a distributed version control system (DVCS), with Git, you can still have an official, canonical repository where all changes to the software must be stored. With Git, because each developer's repository is complete, their work doesn't need to be constrained by the availability and performance of the "central" server. During outages or while offline, developers can still consult the full project history. Because Git is flexible as well as being distributed, you can work the way you are accustomed to but gain the additional benefits of Git, some of which you may not even realise you're missing.

Now that you understand what version control is, what Git is and why software teams should use it, read on to discover the benefits Git can provide across the whole organization.
  
### <span style="color:#3e70b1"> Github
GitHub is an American company that provides hosting for software development version control using Git. It is a subsidiary of Microsoft, which acquired the company in 2018 for $7.5 billion. It offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

GitHub offers plans for free, professional, and enterprise accounts. Free GitHub accounts are commonly used to host open source projects. As of January 2019, GitHub offers unlimited private repositories to all plans, including free accounts. As of May 2019, GitHub reports having over 37 million users and more than 100 million repositories (including at least 28 million public repositories), making it the largest host of source code in the world.
  
### <span style="color:#3e70b1"> GitHub API
Github API Dokument
  
### <span style="color:#3e70b1"> Github Pages
GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub, optionally runs the files through a build process, and publishes a website. You can see examples of GitHub Pages sites in the GitHub Pages examples collection.

You can host your site on GitHub's github.io domain or your own custom domain. For more information, see "(Using a custom domain with GitHub Pages)."

To get started, see "Creating a GitHub Pages site."
  
### <span style="color:#3e70b1"> Google Analytics
Google Analytics Document
  
### <span style="color:#3e70b1"> Jekyll
Jekyll is a simple, extendable, static site generator. You give it text written in your favorite markup language and it churns through layouts to create a static website. Throughout that process you can tweak how you want the site URLs to look, what data gets displayed in the layout, and more.
  
### <span style="color:#3e70b1"> Netlify
Netlify is an all-in-one platform for automating modern web projects. Replace your hosting infrastructure, continuous integration, and deployment pipeline with a single workflow. Integrate dynamic functionality like serverless functions, user authentication, and form handling as your projects grow.

To get started with Netlify, learn how to create deploys. Options for creating deploys range from connecting a Git repository for continuous deployment to publishing a site folder with drag and drop. Use the Deploy to Netlify button on our JAMstack templates to create a Git repository linked to a Netlify site that you can experiment with.

### <span style="color:#fbc993"> Netlify CMS 
Netlify CMS is an open source content management system for your Git workflow that enables you to provide editors with a friendly UI and intuitive workflows. You can use it with any static site generator to create faster, more flexible web projects. Content is stored in your Git repository alongside your code for easier versioning, multi-channel publishing, and the option to handle content updates directly in Git.

At its core, Netlify CMS is an open-source React app that acts as a wrapper for the Git workflow, using the GitHub, GitLab, or Bitbucket API. This provides many advantages, including:

- Fast, web-based UI: With rich-text editing, real-time preview, and drag-and-drop media uploads.
- Platform agnostic: Works with most static site generators.
- Easy installation: Add two files to your site and hook up the backend by including those files in your build process or linking to our Content Delivery Network (CDN).
- Modern authentication: Using GitHub, GitLab, or Bitbucket and JSON web tokens.
- Flexible content types: Specify an unlimited number of content types with custom fields.
- Fully extensible: Create custom-styled previews, UI widgets, and editor plugins.

#### Netlify CMS vs. Netlify
Netlify.com is a platform you can use to automatically build, deploy, serve, and manage your frontend sites and web apps. It also provides a variety of other features like form processing, serverless functions, and split testing. Not all Netlify sites use Netlify CMS, and not all sites using Netlify CMS are on Netlify.

The folks at Netlify created Netlify CMS to fill a gap in the static site generation pipeline. There were some great proprietary headless CMS options, but no real contenders that were open source and extensible—that could turn into a community-built ecosystem like WordPress or Drupal. For that reason, Netlify CMS is made to be community-driven, and has never been locked to the Netlify platform (despite the name).

### <span style="color:#3e70b1"> React
React is a JavaScript library for building user interfaces. It is the view layer for web applications.

At the heart of all React applications are components. A component is a self-contained module that renders some output. We can write interface elements like a button or an input field as a React component. Components are composable. A component might include one or more other components in its output.

Broadly speaking, to write React apps we write React components that correspond to various interface elements. We then organize these components inside higher-level components which define the structure of our application.

For example, take a form. A form might consist of many interface elements, like input fields, labels, or buttons. Each element inside the form can be written as a React component. We'd then write a higher-level component, the form component itself. The form component would specify the structure of the form and include each of these interface elements inside of it.

Importantly, each component in a React app abides by strict data management principles. Complex, interactive user interfaces often involve complex data and application state. The surface area of React is limited and aimed at giving us the tools to be able to anticipate how our application will look with a given set of circumstances. 
  
### <span style="color:#3e70b1"> React-Static
React Static is a framework designed to help everyone painlessly build next generation, high-performance websites for the web.

With react-static you can deliver an amazing experience for your users and developers alike, without compromising React in any way. It’s insanely fast, touts fantastic SEO capabilities, and is probably the most React-friendly static-site library on the internet.
  
### <span style="color:#3e70b1"> Sanity.io
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Sass
CSS’i bir programlama diline benzer yapıyla geliştirmemizi sağlayan, sürekli ihtiyaç duyduğumuz ve CSS’te bulunmayan birçok özelliği kullanarak, daha pratik ve okunaklı kod yazmamıza olanak verir. Binlerce satırlık CSS kodlarını daha hızlı yazmamızı, daha düzenli bir stil dosyası oluşturmamıza olanak tanır.
  
### <span style="color:#3e70b1"> Serverless DB
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Service Workers
A Service Worker is a script that executes in the background, in a separate thread from the browser UI. Service worker cache makes it possible for a web site to function offline. They enable deep platform integration, like rich caching, push notifications and background sync.

Service workers are the core technology used in Progressive Web Applications.

Service workers are designed to be an extensible platform, additional features are currently being planned.

They can't access the DOM, but can intercept all network request. This allows developers the opportunity to control how requests are handled, providing a rich way to make websites work offline.

Service workers are have been called a game changer for the web. I don't think that is a simple exaggeration, because they enable many much needed capabilities and make the core architecture I used for years native.

Service Workers sound amazing!

This is the key technology or modern web API behind Progressive Web Applications. Without a service worker a website is just a website, add a service worker and you now have an application.

There are some key features about service workers you need to understand:

-  Service Worker is a JavaScript File
-  They execute on a separate thread from the UI
-  They cannot access the DOM directly
-  There is a life cycle or series of events a service worker flows through to become active, explained later
-  They are only live while being used, so no battery strain
-  They are isolated to the origin or domain they are registered with
-  Service Workers require HTTPS
-  Can send messages to and from the UI
-  Do not require an open web page to function
-  Are supported by all major browsers, including iOS Safari
-  Are similar to Web Workers, but better in many ways
  
### <span style="color:#3e70b1"> Vanilla JS & CSS
As JAMstack projects grow really large, new changes might require re-deploying hundreds of files. Uploading these one at a time can cause inconsistent state while the process completes. You can avoid this with a system that lets you do “atomic deploys,” where no changes go live until all changed files have been uploaded.
  
### <span style="color:#3e70b1"> Web App Manifest
This specification defines a JSON-based manifest file that provides developers with a centralized place to put metadata associated with a web application. This metadata includes, but is not limited to, the web application's name, links to icons, as well as the preferred URL to open when a user launches the web application. The manifest also allows developers to declare a default orientation for their web application, as well as providing the ability to set the display mode for the application (e.g., in fullscreen). Additionally, the manifest allows a developer to "scope" a web application to a URL. This restricts the URLs to which the manifest is applied and provides a means to "deep link" into a web application from other applications.

Using this metadata, user agents can provide developers with means to create user experiences that are more comparable to that of a native application.

This specification also defines the manifest link type as a declarative means to associate a document with a manifest.
  
### <span style="color:#3e70b1"> Webpack
Webpack is an open-source JavaScript module bundler. It is a module bundler primarily for JavaScript, but it can transform front-end assets like HTML, CSS, and images if the corresponding loaders are included. Webpack takes modules with dependencies and generates static assets representing those modules.

Webpack takes the dependencies and generates a dependency graph allowing web developers to use a modular approach for their web application development purposes. It can be used from the command line, or can be configured using a config file which is named webpack.config.js. This file is used to define rules, plugins, etc., for a project. (Webpack is highly extensible via rules which allow developers to write custom tasks that they want to perform when bundling files together.)

Node.js is required for using Webpack.

Webpack provides code on demand using the moniker code splitting. The Technical Committee 39 for ECMAScript is working on standardization of a function that loads additional code: "proposal-dynamic-import".
  
----

# CMS Platforms

### List of Git-based CMS Platforms
Forestry - https://forestry.io
Crafter CMS - https://craftercms.org
Netlify CMS - https://www.netlifycms.org
Publii - https://getpublii.com
Prose - http://prose.io

### List of API-based CMS Platforms
Storyblok - Contentful - Sanity - Dato CMS - Prismic - Ghost - Strapi - Cloud CMS - Directus - Rooftop - https://www.storyblok.com/
https://www.contentful.com
https://sanity.io
https://www.datocms.com/
https://prismic.io
https://ghost.org
https://strapi.io
https://www.cloudcms.com
https://directus.io
https://www.rooftopcms.com

### Resource
https://travis-ci.com/

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

