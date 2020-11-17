---
layout: single
permalink: /about/overview
title: "Overview"
last_modified_at: 2020-05-01T10:15:22-04:00
sidebar: true
sidebar:
  nav: "about-wct"
---

The Web Curator Tool (WCT) is a tool for managing the selective web harvesting process, and is designed for use in libraries by non-technical users. It is integrated with v3 of the Heritrix web crawler which is used to download web material (but technical details are handled behind the scenes by system administrators).

## The WCT supports
- Harvest Authorisation: getting permission to harvest web material and make it available.
- Selection, scoping and scheduling: what will be harvested, how, and how often?
- Description: Dublin Core metadata.
- Harvesting: Downloading the material at the appointed time with the Heritrix web harvester deployed on multiple machines.
- Quality Review: making sure the harvest worked as expected, and correcting simple harvest errors.
- Submitting the harvest results to a digital archive.

## What it is NOT
- It is NOT a digital archive or document repository - It is not appropriate for long-term storage - It submits material to an external archive
- It is NOT an access tool - It does not provide public access to harvested material - (But it does let you review your harvests) - You should use Wayback or WERA as access tools
- It is NOT a cataloguing system - It does allow you to record external catalog numbers - And it does allow you to describe harvests with Dublin Core metadata
- It is NOT a document management system - It does not store all your communications with publishers - But it may initiate these communications - And it does record the outcome of these communications

### The Web Curator Tool supports a harvesting workflow comprising a series of specialised tasks:
- selecting an online resource
- seeking permission to harvest it and make it publicly accessible
- describing it
- determining its scope and boundaries
- scheduling a web harvest or a series of web harvests
- performing the harvests
- performing quality review and endorsing or rejecting the harvested material
- and depositing endorsed material in a digital repository or archive.

Most current web archiving activities rely heavily on the technical expertise of the harvest operators. The Web Curator Tool, on the other hand, makes harvesting the responsibility of users and subject experts (rather than engineers and system administrators) by handling automatically the technical details of web harvesting. The tool is designed to operate safely and effectively in an enterprise environment, where technical support staff can maintain it.

