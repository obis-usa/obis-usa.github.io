---
layout: post
title: IPT Management
summary: Markdown is a way to style text on the web. You control the display of the document; formating words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in.
featured-img: emile-perron-190221
categories: Guides
---

# How to Guide for Managing the OBIS-USA IPT

## Resources:
* IPT Manual: https://ipt.gbif.org/manual/en/ipt/latest/
* GitHub Repository: https://github.com/gbif/ipt
* OBIS-USA IPT: https://ipt-obis.gbif.us/

## Contacts

If all else fails, use the following help desks to ask questions:

* helpdesk@gbif.org
* helpdesk@obis.org

## Background on the OBIS-USA IPT Installation

The [Integrated Publishing Toolkit (IPT)](https://github.com/gbif/ipt) is a free, open source software tool provided by the Global Biodiversity Information Facility (GBIF) and used to publish and share biodiversity datasets through the GBIF network. The IPT can also be configured with a DataCite account in order to assign DOIs to datasets, thus transforming it into a data repository.

The [OBIS-USA IPT](https://ipt-obis.gbif.us/) was installed originally at the U.S. Geological Survey (USGS) under the National Biological Information Infrastructure (NBII) program and then the Science Analytics and Synthesis program. In 2022, the OBIS-USA IPT was moved to being hosted on GBIF infrastructure (along with the GBIF-US IPT) which is located in Copenhagen, Denmark.

## Updating the OBIS-USA IPT

GBIF will automatically update the IPT to the most recent version. If this is not done in a reasonable amount of time, send an email to the GBIF HelpDesk at helpdesk@gbif.org

### Step-by-Step
1. Review https://ipt.gbif.org/manual/en/ipt/latest/releases and the notes about what changed.
1. Check monthly to see if IPT has been updated.
1. If not updated, send an email to helpdesk@gbif.org

## Updating the OBIS-USA IPT Extensions

Darwin Core consists of a [core set of terms](https://dwc.tdwg.org/terms/) as well as a [set of extensions](https://rs.gbif.org/extensions.html) to augment the core. The Darwin Core standard and its extensions is maintained by [TDWG (the Taxonomic Databases Working Group)](https://www.tdwg.org/) which is a vibrant, active community (please consider joining and contributing to the maintainance). Given the active nature of the standard and the extensions they need to be updated when changes are made. To update the extensions, follow the step-by-step guide below.

### Step-by-Step
1. Log into the IPT as an **Administrator**: https://ipt-obis.gbif.us/
2. Browse to **Administration**: https://ipt-obis.gbif.us/admin/
   <img width="628" height="197" alt="image" src="https://github.com/user-attachments/assets/b8364aec-5042-4c4d-b8c7-24f02a3c1ab7" />
4. Click the **View** link in Darwin Core Types and Extensions. https://ipt-obis.gbif.us/admin/extensions.do
   <img width="334" height="224" alt="image" src="https://github.com/user-attachments/assets/3af24ba8-0d07-41dc-a9c8-97885e83eea3" />
1. Review if any Darwin Core types or extensions need to be updated.
2. If they need to be updated, click **Update**.
3. You will be prompted with ```You are about to update this extension to the latest version. Following the update, affected resources should be reviewed and republished. Do you still want to update?```
4. Confirm
5. Check all of the mappings to ensure everything is mapping to where it needs to be.

Once updated, the page should say "All installed extensions use the latest version" as shown below:
<img width="574" height="228" alt="image" src="https://github.com/user-attachments/assets/90f07b29-beff-471b-adf1-4c2a4258f550" />


## Defining roles for OBIS-USA IPT management

The roles for managing the IPT include:
* IPT Node Manager - The data manager who publishes data, provides support to individual data managers on publishing, ensures community awareness.
* IPT IT support - The support staff who help with technical issues related to the IPT (eg. updating IPT, moving backend around, etc.)

## OBIS-USA IPT Node Manager responsibilities
Most of what the IPT manager does is contained in the Administration Dashboard of the IPT. The node manager should be aware of updates to the IPT software by joining 
the GBIF IPT Mailing list (https://lists.gbif.org/mailman/listinfo/ipt/) and following the IPT GitHub repository (https://github.com/gbif/ipt). 

* Manage user accounts including adding new users (four types of accounts) and periodically reviewing user account access to remove access for stale accounts
* Adds associated organizations
* Keeps the IPT settings up to date
* Updates the GBIF Registration Options as needed
* Updates the Darwin Core Types and Extensions as needed (there is a mailing list that GBIF hosts to alert IPT managers about updates)
* Acts as the conduit between global data integration entities like OBIS and GBIF and data providers on any issues with datasets
* Can register datasets with OBIS
* Can register datasets with GBIF
* Can register datasets with appropriate communities

## How does a data manager request reviews of their datasets?

* Log an issue at https://github.com/ioos/bio_data_guide/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22data%20help%22.

## Cleaning out datasets on the OBIS-USA IPT

In some cases there are datasets that were built for testing and demonstration purposes. On a yearly(?) basis, those datasets should be cleared out as to not confuse users. 

To delete a dataset: 
1. Browse to the IPT overview page for the dataset.
2. Click the **Delete** red button.
3. It will ask you to confirm your selection.

---
