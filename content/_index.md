Quite simply, **GitHub** and **GitHub Pages**, combined with a **static site generator** are one of the most cost-efficient (free), reliable, time-tested, and secure ways to host a website.

It is possible to host such website and have a Princeton University custom domain. This page provides instruction on how to do that.

- **GitHub is a free website for the long-term storage of certain files.** GitHub is a website that developers uses to store source code, because it tracks every single change made to the files, and is very reliable. GitHub has continuously hosted many projects for over a decade for free.

- **GitHub Pages allows you to host a website for free.** GitHub Pages is a feature of GitHub that allows you to host a website for free, using the files stored in your GitHub repository. You can use GitHub Pages to host a website for your project, or even a personal website.

## HOWTO: GitHub Pages from `xxxxxx.princeton.edu`

It is possible to host a website on GitHub Pages, but to have a Princeton University domain name, such as this website, hosted from the repository [`jlumbroso/github-pages-princeton`](https://github.com/jlumbroso/github-pages-princeton/) and served on the domain name [`github-pages.princeton.edu`](https://github-pages.princeton.edu/).

- You will need to request [an alias be created in the DNS through the ServiceNow form](https://princeton.service-now.com/service?id=sc_cat_item&sys_id=db24940a4ff92e0018ddd48e5210c750).

  - In this form, select the option "_DNS Alias a cloud-hosted site (show mysite.com as if it is mysite.princeton.edu)_";
  - In this form, for "_Cloud URL being aliased (destination)_", enter the URL of the GitHub Pages relay URL which is `github-pages.princeton.edu`.

- It may take about a week for this domain name to be created for you.

- Once it is created, you can follow [GitHub's instruction to setup a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).

**Examples of websites:**

- This [GitHub Pages at Princeton University](https://github-pages.princeton.edu) information page
- [Mark Braverman's professional page](https://mbraverm.princeton.edu/)
- The page of the course [COS 513/SML 513 — Foundations of Probabilistic Modeling](https://cos513.princeton.edu/) taught by Adji Bousso-Dieng

## HOWTO: GitHub Pages from `xxxxxx.cs.princeton.edu`

The subdomain `*.cs.princeton.edu` is managed not by OIT, but by CS staff, the local IT staff for the Department of Computer Science.

- Contact CS staff at [csstaff@cs.princeton.edu](mailto:csstaff@cs.princeton.edu) to request a subdomain be created for you (by aliasing from that domain to `github-pages.cs.princeton.edu`).

- Follow the same instructions as above to setup a custom domain on your GitHub Pages website.

**Examples of websites:**

- The Department of Computer Science's [Introductory Lab's website](http://introlab.cs.princeton.edu/)
