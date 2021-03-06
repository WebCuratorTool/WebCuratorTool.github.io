---
title:  "Go-live of WCT 3 successful at National Libraries of the Netherlands and New Zealand"
excerpt: "The National Library of the Netherlands (KBNL) is the first organization to take the brand new version 3 of the Web Curator Tool (WCT) into production."
last_modified_at: 2020-12-07T08:06:00-05:00
authors: [jeffrey_van_der_hoeven, trienka_rohrbach, hanna_koppelaar, andrea_goethals]
---

The National Library of the Netherlands (KBNL) is the first organization to take the brand new version 3 of the Web Curator Tool (WCT) into production. As a faithful user of the WCT starting in 2007 the KBNL has since then harvested more than 18,000 websites successfully with the WCT as a workflow management solution for scheduling, harvesting and quality analysis. With WCT 3 into production, the KBNL has improved reliability of the WCT environment and is ready for future enhancements. Jeffrey van der Hoeven, head of the Digital Preservation dept at KBNL: “I’m very proud that our cooperation with NLNZ is working out so well. WCT version 3 is the result of that joint development effort.”

The National Library of New Zealand (NLNZ) has also successfully put version 3 of the WCT into production. As one of the institutions that first developed the WCT in 2006, NLNZ has since that time been using the WCT to manage its selective web harvesting. Having migrated to version 3, NLNZ now has up-to-date tools at the heart of its web archiving programme. Andrea Goethals, Manager of Digital Preservation at NLNZ: “It was very fortunate for us that the KBNL had very similar needs as us for a web archiving tool that can be put in the hands of our curators. By collaborating on developing WCT with us, we all end up with a much better solution.”

#### What’s new in version 3?

With version 3 you get a much easier installation process, well documented and tested, and an up-to-date technical framework behind the scenes. With this solid foundation in place, you will also be in a much better position to receive future updates with new functionality.

A significant change in version 3 that System Administrators should be aware of is that WCT no longer requires an application container, such as Tomcat to run it. Instead, WCT has now been migrated to run with Spring Boot, which uses an embedded Tomcat server. 

#### Why choose WCT?

Jeffrey: “Reliability and full control over our web harvesting process is very important to us. Meanwhile, we believe that collection specialists are often not techies and need easy-to-use tools at hand. Therefore, the WCT is an excellent piece of equipment for us.”

In 2018, version 2 of the WCT was released publicly containing long-awaited improvements on crawling techniques by integrating the latest Heritrix crawl engine H3 into WCT. But under the hood, a lot of the technical libraries and scripts of WCT were outdated due to lack of maintenance for several years before. Also, installation and migration could be a quite challenging process.

Meanwhile the WCT still delivered strong crawling results and has shown to be a powerful tool in performing orchestrated selective web harvests. Both National Library of New Zealand and KBNL recognized that investing in the WCT is worthwhile. In 2017 this resulted in the start of a strong cooperation between the two organizations to revamp the WCT and bring the software a major uplift, first technically and later on functionally.

Trienka Rohrbach, service administrator at KBNL states the usefulness of WCT for her library: “With the WCT I’m capable of supporting our collection specialists at the library in such a way that they can schedule crawls and perform in-depth analysis on their own without the need to dive into a lot of technical details.”

Since the successful relaunch of WCT with version 2, it took about two years of development to upgrade the whole software stack of WCT into a modern foundation while not compromising reliability and backwards compatibility with previous WCT-versions currently in use across the web archiving community.

#### What is to be expected next?
The WCT development team has already started development on huge functional improvements such as a neat integration with the Webrecorder, graph-like visualization of web crawls and better screenshot capturing. We expect next releases to be more lightweight and more frequent so please stay in touch with the [WCT community](https://webcuratortool.org/about/collaboration). Hanna Koppelaar, software developer at KBNL: “We’re still continuously improving the WCT code base and reducing technical debt, but the focus for version 4 will be adding new features and improvements requested by our users.”

[Click here](https://webcuratortool.readthedocs.io/en/latest/guides/quick-start-guide.html#installation) to start downloading the new WCT release 3.

Want to try it first locally? [Download our demo-version ready for use in Virtual Box](https://webcuratortool.org/guide/).
