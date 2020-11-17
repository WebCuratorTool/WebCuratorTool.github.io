---
title:  "World Wide Webarchiving: Upgrading the Web Curator Tool"
excerpt: "The Web Curator Tool (WCT) is a workflow management application designed for selective web archiving. It was created for use in libraries and other digital heritage collecting organisations, and supports collection by non-technical users while still allowing complete control of the web harvesting process. The WCT is a tool that supports the selection, harvesting and quality assessment of online material when employed by collaborating users in a library environment."
last_modified_at: 2018-04-12T08:06:00-05:00
---

The Web Curator Tool (WCT) is a workflow management application designed for selective web archiving. It was created for use in libraries and other digital heritage collecting organisations, and supports collection by non-technical users while still allowing complete control of the web harvesting process. The WCT is a tool that supports the selection, harvesting and quality assessment of online material when employed by collaborating users in a library environment. The application is integrated with the existing Heritrix web crawler and supports key processes such as permissions, job scheduling, harvesting, quality review, and the collection of descriptive metadata. The WCT allows institutions to capture almost any online resource. These artefacts are handled with all possible care, so that their integrity and authenticity is preserved.

The WCT was developed in 2006 as a collaborative effort by the [National Library of New Zealand](http://www.natlib.govt.nz/) (NLNZ) and the [British Library](http://www.bl.uk/) (BL), initiated by the [International Internet Preservation Consortium](http://www.netpreserve.org/) (IIPC) as can be read in the original [documentation](http://opac.lianza.org.nz/cgi-bin/koha/opac-detail.pl?bib=121). The WCT is open-source and available under the terms of the Apache Public License. The project was moved in 2014 from Sourceforge to Github. The latest ‘binary’ release of the WCT, v1.6.3, was published in July 2017 on the Github page of NLNZ. Even after 12 years, the WCT still continues as one of the most common, open-source enterprise solutions for web archiving. It has an active user forum on Github and [Slack](https://webcurator.slack.com/).

From January 2018 onwards, NLNZ has been collaborating to upgrade the WCT with the [Koninklijke Bibliotheek – National Library of the Netherlands](https://www.kb.nl/) (KB-NL) and adding new features to make the application future-proof. This involves learning the lessons from the previous development and recognising the advancements and trends occurring in the web archiving community. The objective is to get the WCT to a platform where it can keep pace with the requirements of archiving the modern web. Further, the Permission Request module will be extended to fit the Dutch situation which lacks a legal deposit for digital publications.

The first step in that process was decoupling the WCT from the old [Heritrix 1.x web crawler](http://crawler.archive.org/index.html), and allowing the WCT to harvest using the updated [Heritrix 3.x](https://github.com/internetarchive/heritrix3) version. A proof of concept for this change was successfully developed and deployed by the NLNZ, and has been the basis for a joint development work plan. The project will be extensively documented.

The NLNZ has been using the WCT for its selective web archiving programme since January 2007, KB-NL since 2009. In 2008 NLNZ published an [article](http://www.dlib.org/dlib/may08/paynter/05paynter.html) describing their experience using WCT in a production environment. However, the software had fallen into a period of neglect, with mounting technical debt: most notably its tight integration with an out-dated version of the Heritrix web crawler. While the last public release of the WCT is still used day-to-day in various institutions, this release has essentially reached its end-of-life as it has fallen further and further behind the requirements for harvesting the modern web. The community of users have echoed these sentiments over the last few years.

During 2016-2017 the NLNZ conducted a review of the WCT and how it fulfils business requirements, and compared the WCT to alternative software/services. The NLNZ concluded that the WCT was still the closest solution to meeting its requirements – provided the necessary upgrades could be done, namely a change to use the modern Heritrix 3 web crawler. Through a series of fortunate conversations the NLNZ discovered that another WCT user, KB-NL, was going through a similar review process and had reached the same conclusions. This led to collaborative development between the two institutions to uplift the WCT technically and functionally to be a fit for purpose tool within these institutions’ respective web archiving programmes.

### Who are involved:

#### National Library of New Zealand:

- Steve Knight
- Andrea Goethals
- Ben O’Brien
- Gillian Lee
- Susanna Joe
- Sholto Duncan

#### Koninklijke Bibliotheek:

- Peter de Bode
- Jeffrey van der Hoeven
- Hanna Koppelaar
- Tymen Kwant
- Barbara Sierman
- René Voorburg
- Kees Teszelszky
