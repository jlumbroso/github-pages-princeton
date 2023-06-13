Quite simply, **GitHub** and **GitHub Pages**, combined with a **static site generator** are one of the most cost-efficient (free), reliable, time-tested, and secure ways to host a website.

It is possible to host such website and have a Princeton University custom domain. This page provides instruction on how to do that.

- **GitHub is a free website for the long-term storage of certain files.** GitHub is a website that developers uses to store source code, because it tracks every single change made to the files, and is very reliable. GitHub has continuously hosted many projects for over a decade for free.

- **GitHub Pages allows you to host a website for free.** GitHub Pages is a feature of GitHub that allows you to host a website for free, using the files stored in your GitHub repository. You can use GitHub Pages to host a website for your project, or even a personal website.

➡️ **To get started in 5 minutes, (1) [register a GitHub account](https://github.com/signup), then (2) [click here to create a free website](https://github.com/jlumbroso/hugo-github-bearblog-template/generate); once it is configured, follow the instructions below to configure your Princeton University custom domain.** ⬅️

For more information reach out to [Jérémie Lumbroso](https://www.cs.princeton.edu/people/profile/lumbroso).

## HOWTO: GitHub Pages from `xxxxxx.princeton.edu`

It is possible to host a website on GitHub Pages, but to have a Princeton University domain name, such as this website, hosted from the repository [`jlumbroso/github-pages-princeton`](https://github.com/jlumbroso/github-pages-princeton/) and served on the domain name [`github-pages.princeton.edu`](https://github-pages.princeton.edu/).

- You will need to request [an alias be created in the DNS through the ServiceNow form](https://princeton.service-now.com/service?id=sc_cat_item&sys_id=db24940a4ff92e0018ddd48e5210c750).

  - In this form, select the option "_DNS Alias a cloud-hosted site (show mysite.com as if it is mysite.princeton.edu)_";
  - In this form, for "_Cloud URL being aliased (destination)_", enter the URL of the GitHub Pages relay URL which is `github-pages.princeton.edu` (the relay is the OIT-approved way to express the website is a GitHub Pages website, and helps avoid having to enter and maintain IP addresses).

- It may take about a week for this domain name to be created for you.

- Once it is created, you can follow [GitHub's instruction to setup a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).

**Examples of websites:**

- [`github-pages.princeton.edu`](https://github-pages.princeton.edu): This GitHub Pages at Princeton University information page
- [`mbraverm.princeton.edu`](https://mbraverm.princeton.edu/): Mark Braverman's professional page
- [`cos513.princeton.edu`](https://cos513.princeton.edu/): The page of the course _COS 513/SML 513 — Foundations of Probabilistic Modeling_ taught by Adji Bousso-Dieng

## HOWTO: GitHub Pages from `xxxxxx.cs.princeton.edu`

The subdomain `cs.princeton.edu` is managed not by OIT, but by CS staff, the local IT staff for the Department of Computer Science.

- Contact CS staff at [csstaff@cs.princeton.edu](mailto:csstaff@cs.princeton.edu) to request a CNAME entry be created for you aliasing from that `xxxxxx.cs.princeton.edu` domain to `github-pages.princeton.edu`.

- Follow the same instructions as above to setup a custom domain on your GitHub Pages website.

**Examples of websites:**

- [`introlab.cs.princeton.edu`](http://introlab.cs.princeton.edu/): The Department of Computer Science's undergraduate-staffed Introductory Lab's website
- [`competitive-programming.cs.princeton.edu`](https://competitive-programming.cs.princeton.edu/): Princeton University's Competitive Programming website run by [Pedro Paredes](https://www.cs.princeton.edu/~paredes/)
