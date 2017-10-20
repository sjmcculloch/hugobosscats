---
title: "Form Complete"
date: 2017-10-20T12:03:33+11:00
draft: false
title: "Netlify Questions"
layout: empty
---

<header>
    <div class="container">
        <div class="row">
            <div class="col-lg-12">
                <img class="img-responsive" src="img/{{ with .Site.Params.header.image }}{{ . }}{{ else }}profile.png{{ end }}" alt="">
                <div class="intro-text">
                    <span class="name">Answers</span>
                </div>
            </div>
        </div>
    </div>
</header>
<section>
    <div class="container">
        <div class="row">
            <div class="col-lg-12">
                <h3>Most favorite support things:</h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-12">
                <p>-- Dig through server logs to troubleshoot a customer's website behavior</p>
                <p>-- Debug a customer's build using a programming language and framework that you've never seen before</p>
                <p>-- Work with people to figure out if Netlify's service can solve a particular workflow or integration challenge they have</p>
                <p>-- Suggest and champion improvements to the product and workflow to your colleagues in and out of support</p>
                <p>-- Set up your own copy of several static site frameworks for debugging</p>
                <p>&nbsp;</p>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <h3>Least favorite support things:</h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-12">
                <p>-- Manage a support team</p>
                <p>-- Work with prospective customers to explain our service and the pricing model (pricing is always a tricky subject)</p>
                <p>-- Help manage communications during a service outage</p>
                <p>-- Create video tutorials to help teach users a specific feature or use case (it can be very time consuming)</p>
                <p>-- Find and recruit teammates for the support team</p>
                <p>&nbsp;</p>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <h3>What is your favorite thing about providing technical support?</h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-10 col-lg-offset-1">
                <p>Seeing the end products that customers produce on the platform and helping them along the path of self sufficiency. Furthermore, there are a number of learnings you can take onboard with each support ticket that can feed back into the platform for improvement - that part is exciting to me.</p>
                <p>&nbsp;</p>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <h3>What did you think of our service during the time you used it?</h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-10 col-lg-offset-1">
                <p>The interface is amazing along with the documentation and platform.</p>
                <p>There was a bit of a jump as a free user when needing help beyond the documentation, the gitter channel is good but it is difficult to keep track of. </p>
                <p>I'm a fairly technical user so I was able to resolve my issues but I can see some people potentially giving up. 
                    My issue was around some image paths not translated into CDN paths for a Jekyll site. This was due to a plugin I was using that was writing full paths instead of absolute relative. I ended up copying &amp; [modifying the plugin](https://github.com/sjmcculloch/smccblog/blob/master/_plugins/jekyll-picture-tag.rb).</p>
                <p>&nbsp;</p>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <h3>Tell about how you made your site and why you chose the tools you did.  </h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-10 col-lg-offset-1">
                <p>The very first site I made on Netlify was purely out of curiosity. I stumbled upon an article [http://hawksworx.com/blog/isomorphic-rendering-on-the-jam-stack/](that talked about the JAMStack a year ago).</p>
                <p>The article extolled the virtues of Netlify as the build service &amp; host in the solution. I had already done a great deal of work in the CMS world and in particular content modelling with the usage of a headless CMS so it looked like a neat solution.  </p>
                <p>I'm the type of person that often needs to build things for myself to understand, so I used the above solution as a template and built a small blog site using Contentful &amp; Netlify. [It also has AMP enabled](https://www.makemutcoins.com/amp/investing-in-players-for-profit). I also [wrote about my experiences](https://www.smcculloch.com/code/netlify-contentful-jamstack).</p>
                <p>For the solution today, I hadn't used Hugo before so that is why I chose that as a solution. My [current blog](//www.smcculloch.com) is built using Jekyll. </p>
                <p>&nbsp;</p>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <h3>Could you give us a suggestion to improve this test or the job posting?</h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-10 col-lg-offset-1">
                <p>I quite like this test as it's concise but yet still allows a small amount of creativity. The job posting I happened on by accident (a random twitter retweet), so my only suggestion might be to increase visibility to potential employees (which are most likely to be among your customers).</p>
                <p>You may also consider asking people to secure their sites to prevent copy/paste as you do this in the future.</p>
                <p>&nbsp;</p>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <h3>Provide a link to documentation for a technical/developer-focused product, that you think are well done, and briefly explain why you think they are well done.</h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-10 col-lg-offset-1">
                <p>I went to the same university as a few friends that started [Campaign Monitor](https://www.campaignmonitor.com/), they even attended my sessions when I used to run a .NET User Group locally for many years. I've always found their product and [documentation easy to use](https://www.campaignmonitor.com/api/)</p>
                <p>The documentation is visually appealing and is well broken up. My only suggestion to them would be to have some [inline call functionality like contentful does](https://www.contentful.com/developers/docs/references/content-delivery-api/#/reference/entries/entries-collection).</p>
                <p>&nbsp;</p>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <h3>Why do you think SSL/HTTPS is important?</h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-12">
                <p>-- Security &amp; Privacy - all communication between client and server is encrypted. Essential for any site that has any kind of form submission or when you are on free Wi-Fi services.</p>
                <p>-- SEO &amp;Analytics - Google rewards sites running SSL and for Analytics, you only get referrers from HTTPS sites if you support it as well. </p>
                <p>-- Performance - HTTP/2 only works when HTTPS is enabled.</p>
                <p>&nbsp;</p>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <h3>Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users</h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-10 col-lg-offset-1">
                <p>The first major problem is that of terminology and frequency. Less-technical users have no idea what a CNAME, ANAME or ALIAS records and have to look it up each time. In general, it's a task that is not performed regularly, so it's usually a set and forget procedure that doesn't result into knowledge retained. </p>
                <p>Second is the distributed nature of DNS, if configured incorrectly, it may take a while for the problem to unravel and potentially have a negative impact on a client's infrastructure. It's not as simple as testing a script out or turning a feature on/off.</p>
                <p>&nbsp;</p>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <h3>A customer writes in saying their “site won’t build”.  Compose your best short (2-paragraph) customer-facing answer without any additional data, that could be useful in the generic case but would also lead to a customer providing a more actionable response.</h3>
            </div>
        </div>
        <div class="row ">
            <div class="col-lg-10 col-lg-offset-1">
            <p>
                Hello, 
            </p>
            <p>
                Thank you for contacting the Netlify team. 
            </p>
            <p>
                My name is Scott, I am a support engineer and I'll be assisting you with this issue.
            </p>
            <p>
                To allow me to help, can you tell me about the type of site and what build tools you are using? Providing your build is working locally, I can dig further into the root cause.
            </p>
            <p>
                In the meantime, we generally find that most build failures are caused by incompatible specification of versions in the build tool environment. For NodeJS, this would be package.json. For Python or Ruby, maybe a requirements.txt or a Gemfile. 
            </p>
            <p>
                At Netlify we use this environment by default:
            </p>
            <p>
                - Node.js - version 6.11.4 (with npm version 3)
                - Ruby - version 2.1.2
                - Python - version 2.7
                - PHP - version 5.5.9
            </p>
            <p>
                If you want to know more about how our build system works and additional debugging techniques, we have an article here that may help:
            </p>
            <p>
                https://www.netlify.com/blog/2016/10/18/how-our-build-bots-build-sites/
            </p>
            </div>
        </div>
    </div>
</section>