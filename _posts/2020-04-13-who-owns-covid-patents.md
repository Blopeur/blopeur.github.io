---
layout: post
published: true
title: "Who owns COVID-19 Related Patents: A Quantitative analysis"
description: "We look into the public patents repositories to find out who has been filling  COVID-19 related patents, in general, and more specifically for diagnostics and treatment solution. We also took a look at respirators and masks patents as these technologies are also highly relevant to the current pandemic management."

picture: covid.gif
iosurl: who-owns-covid-patents-safari-ios.html

label_default: "Covid-19"
label_primary: "Patent"
label_success: "Open source"
label_info: "dataset"
---
<!-- Main Container -->

Over the past couple of weeks, we have seen a [number](https://www.facebook.com/theundergroundresistancenetwork/photos/a.1601471479892145/2754419914597290/?type=3&theater) of [claims](https://www.facebook.com/photo.php?fbid=181551143216518&set=a.108489467189353&type=3&theater) on social media saying that a patent for coronavirus was filed in 2015. While this new virus has commonly been referred to by the media and others as just "coronavirus", it is just one type within this family of viruses. Hence the confusion as a patent application from 2015 [does exist](https://patents.justia.com/patent/10130701) for ONE type of coronavirus, but not the same one as that identified in Wuhan. 
However, these stories lead us to wonder who owns patents related to COVID-19?

We decided to take a look into the public patents repositories to find out who has been filling  COVID-19 related patents, in general, and more specifically for diagnostics and treatment solution. We also took a look at respirators and masks patents as these technologies are also highly relevant to the current pandemic management. 

# DataSet: 
The datasets used for this study are open-source and freely available in the following [GitHub repository](https://github.com/Blopeur/covid-patent-dataset).
This repository contains patents datasets related to human coronaviruses and COVID-19.
It contains a cleaned and extended version of the [fantastic coronavirus datasets compiled by lens.org](https://about.lens.org/covid-19/).
We supplemented the Lens.org data by running queries against [the public patent dataset available on Google big query](https://cloud.google.com/blog/products/gcp/google-patents-public-datasets-connecting-public-paid-and-private-patent-data).
You can find the JSON datasets and a description of the query used in the Readme.md in the repository.

**Disclaimer**: these collections are based on public dataset and search queries.
We did some manual editing and refining to eliminate irrelevant or duplicated documents.
We will try to keep these datasets updated.
In the meantime,  if you have any specific question, please email [info@blopeur.com](mailto:info@blopeur.com).


# Methodology :
Patents expire after 20 years of the earliest date of filing upon which priority is claimed.
Owner of patents can request an extension in the USPTO to account for delays.
However, the vast majority of patents expire after 20 years.
Moreover, most countries follow the same rule.
As a result, we only selected patents that have a chance to be still active and enforceable.
We restricted the analysis to the patents with a priority date from the first of January 2000 as any earlier application might have expired already.

Patents are typically first published 18 months after filing, so patents targeted explicitly to this new COVID-19 agent may not appear until June of 2021. Some might happen sooner as some countries are putting in place an accelerated patent process for COVID-19 related applications.
However, there is a wealth of knowledge to mine over the last two decades.
Current, COVID-19 research efforts build on earlier research on severe acute respiratory syndrome (SARS) and the Middle East respiratory syndrome (MERS) as both of this disease are caused by coronaviruses. 
From there, we can gather a set of keywords and CPC definition we can use to build and refine our datasets.

We will also be looking into Surgical masks and respirator related patents as these technologies are also directly related to the treatment of the outbreak.

# MERS and SARS : 

Note on MERS and SARS. MERS is a viral respiratory disease that was first reported in Saudi Arabia in September 2012 and has since spread to 27 countries, according to the World Health Organization. Some people infected with MERS coronavirus (MERS-CoV) develop severe acute respiratory illness, including fever, cough, and shortness of breath.
From its emergence through January 2020, WHO confirmed 2,519 MERS cases and 866 deaths (about 1 in 3). 
Among all reported cases in people, about 80% have occurred in Saudi Arabia.

On the other hand,  Infection with SARS coronavirus (SARS-CoV) can cause a severe viral respiratory illness.
SARS was first reported in Asia in February 2003, though cases subsequently were tracked to November 2002.
SARS quickly spread to 26 countries before being contained after about four months.
More than 8,000 people fell ill from SARS, and 774 died. Since 2004, there have been no reported SARS cases. 

# COVID-19 related patents quantitative analysis

## Broad Keywords Search:

First, by casting a high level and broad keyword search, we find that there were 6135 patents filled matching our search over 20 years. There is a spike 2003 corresponding to the first SARS outbreak in Asia with 1176 patents filled this year alone. For the next 15 years, an average of 250 patents was filled. However, we can notice a significant reduction in application over the past two years. This dip does not mean that there are less COVID-19 related patents filled. The most logical explanation for this dip is that most patents with priority date for these years have not been officially released yet.

<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTc-4zVr5uYNefJ9lQs9iWkjAOdPNFl8jvLxVD04vSnk9hAsYVdIKnkH7EtKTF6ZOnKy8bS8UEzGnfc/pubchart?oid=153144672&amp;format=interactive"></iframe>


If we look at the patents owner distribution, we can notice that the ownership ratio is relatively well distributed.
With the majority of entities owning just a couple of patents.
There are only a few entities owning patents in the double-digit: 
* University of Hong Kong
* Versitech Limited (Commercial arm of University of HongKong)
* Crucell Holland B.V
* National Health Research Institutes
* Glaxosmithkline

Two of those are public institutions, while the rest are private pharmaceutical companies. 


<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTcZof_UilhH1uoeI3pgx8SYkZL9hAsCrmbuzp7k7292crNp_7BaoGSQk86jm1ExDYvyDpSpXrtIlTL/pubchart?oid=1438669421&amp;format=interactive"></iframe>


## Limited Keywords search:

If we refine the search by using a more limited number of keywords, we can see the picture changing slightly.
We now have only 1560 patents matching our search.
We can see the same filling behaviour with a spike in 2003 and an average of 75 fillings per year over the next 15 years. 

<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRS0Op5TVf8A6fYgsSLrAgCUoErb8A-oek9-0g4OTk6Lffm3MXVMw3rXW-1o6EmQLrx51a0R0-_Z9gK/pubchart?oid=1552463898&amp;format=interactive"></iframe>

The ownership spread pattern is also similar, but the entity in the top five changed significantly.
Only the University of Hongkong and Versitech Limited are still present.
The US government seems to own directly or indirectly at least 5% of these patents.
The defunct Theranos Inc. also makes a surprise appearance. 

<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSOBqhxM-LEcq9zCmIROKFUwNpZvsM74-Cv0FyRt9CElNP1pn0PEQe8shdfUIayEWXE9UaeZBN3HDAm/pubchart?oid=1562322448&amp;format=interactive"></iframe>

## Search by CPCs categories

Now if we search for patents using the following CPC definition: 
* C12N2770/20011*
* C07K14/165*
* A61K39/215*
* G01N2333/165*

We get yet another picture of the COVID-19 patents puzzle. 
This time we only have 1084 match, and we can see that the application patterns spike for both the SARS and MERS outbreak.  The University of HongKong is still in the top five, followed closely by Academia Sinica. However, private pharmaceutical corporations are now making the majority of the top 10. 

**CPCs Patents Fillings**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS_hr1v5UiEBh2wR79UjD3KJ4P4JeupxwGBOJ_s_qIwpI5jgZN5NUsEaH95PowTyfhJAShIQbuCUHD0/pubchart?oid=1605646673&amp;format=interactive"></iframe>

**CPCs Patents Owners Breakdown**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRVDhzuqsE8zdpSDyMg2bdHSa_nSOLtORGQR5XFkIlfd3qdqH5ELMY82lg9hayT_-8Xr3-RUy0wW5Zr/pubchart?oid=1350538774&amp;format=interactive"></iframe>


We can note at this stage, after three types of search that very few entities own patents in the double-digit numbers. Only the University of  HongKong Vis consistently ranked in the top five owners. They have been heavily involved in this type of research since the beginning through the Pasteur Research pole.
We can also note that Versitech Limited is also consistently present in the top ten. Versitech Limited is the commercial arm of the University of Hong Kong. Which unsurprisingly is the direct recipient of the research undertaken in HKU. A means a significant amount of patents related to COVID-19 are concentrated in the hand of HKU and its commercials subsidiary. 

However, let us see if this hold when we break down the patent between SARS and  MERS related patents and focus on Diagnostics and Treatments IP.



## MERS and SARS :

**SARS Patents Fillings**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT_M9odleqATDEgkEtg4qae8Zl8P8ym5sRvkIG6arz7OW-JWBobxf-ogW1uGtbA_AOOIpotSMys8IgY/pubchart?oid=502981747&amp;format=interactive"></iframe>

**SARS Patents Owners Breakdown**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSXqiCcDfgPjGdzbdIJP-TZikqvlnKNbRwfEQ3Q-APIwveVI4rCKxHOC7QljPmQHslamAGzdHBASK4O/pubchart?oid=1226729489&amp;format=interactive"></iframe>

**MERS Patents Fillings**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTSoRMDfGMxiGGp9SNKu13gpQJchBzwxWruYJM6mXHWQY-za-yjdgiwhoUSgwQz6AeC0pApsM2GmWLa/pubchart?oid=714375561&amp;format=interactive"></iframe>

**MERS  Patents Owners Breakdown**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSDZAg_a6axP3rNqalnLz38m6Mpd3REQ1SckSbvuabWB7cOScFmm5-4ozOb0DOzobHvbQCdi6YVNcdU/pubchart?oid=876859370&amp;format=interactive"></iframe>

If we restrict our search to MERS and SARS specific patents, we can notice that MERS seems to see a lot less interest compared to SARS. Two hundred fifty-nine patents were filled with an average of 32 per years from 2012. While there were 1390 patents filled for SARS with an average of 73 patents a year.
Patent ownership is also a lot more polarised in the case of MERS with Regeneron Pharmaceuticals owning 10% of the patent pool. Nevertheless, these numbers are due to the low amount of filling. On the other hand, SARS patent follows a similar pattern to the one found in the generic keywords searches. The only surprise it Intermune Inc (now owned by Roche) popping up in the first place. 

### Diagnostics MERS & SARS Patents : 

**SARS Diagnostic Patents Fillings**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT_M9odleqATDEgkEtg4qae8Zl8P8ym5sRvkIG6arz7OW-JWBobxf-ogW1uGtbA_AOOIpotSMys8IgY/pubchart?oid=502981747&amp;format=interactive"></iframe>

**SARS Diagnostic Patents Owners Breakdown**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR-WPwVJ7GgsKMUXdbFkTJlvKnvxZDqA7GV-9daRmIZBAOTUgFBdBmyQMHGFpfEt9NToHpk7KSnfuNk/pubchart?oid=358684455&amp;format=interactive"></iframe>

**MERS Diagnostic Patents Fillings**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQPTNPR7IZ7VEMMkCpm5xXcJiJRdEAF30n4M-WxfNuW6IZtXBnY5CCJgFgPS_FYN4BqYyw3ZEADtA7x/pubchart?oid=2033491308&amp;format=interactive"></iframe>

**MERS Diagnostic Patents Owners Breakdown**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQeAwSCjAkTaqpGz3oqHXl0XAqPswUtk9wRJmkok192SXBhqtYG9fkO7VIbaQym_oda2O3s7TkqOfoV/pubchart?oid=1125531800&amp;format=interactive"></iframe>

If we drill down for diagnostic patents, we can that only a fraction of the overall patent applications are related to the diagnostic solution.
The University of HongKong being once again one of the predominant applicants with [Crucell Holland](https://scrip.pharmaintelligence.informa.com/companies/201300051) (owned by Johnson & Johnson ) close second for SARS diagnostics. 


### Treatments MERS & SARS Patents :

**SARS Treatment Patents Fillings**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTQrRjMQbJpUyPpXmwxt3Nz5dHPRDtsgmtwZZ4TFfzYs1E888PXkQ9yDLRg9uGdFMxhFNgtdwH1Rmr5/pubchart?oid=496699054&amp;format=interactive"></iframe>

**SARS Treatment Patents Owners Breakdown**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRglOAlOUSkggDV8XcEQ-T94-7bw5ND3Y4ViLhDAXhaIkrNE9zNC4WiUzvkOBfGgeqdWhQuLZYHYQWk/pubchart?oid=1437411067&amp;format=interactive"></iframe>

**MERS Treatment Patents Fillings**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT6XeINEHZ04bLD5SsEUxOQJ0shiDCOfoVUNqPwqZu1d_bgnQuNRslWLraHwQrg7IGzNSWXhaHxfp0E/pubchart?oid=342584046&amp;format=interactive"></iframe>

**MERS Treatment Patents Owners Breakdown**
<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQUI4ufRQEbNU2jgY3fedfj5yxzGQc4ebr36zPXRaI1X7iSa6-b08GEOB0P0iTn4IE3DHTVldcsybcx/pubchart?oid=1520254257&amp;format=interactive"></iframe>

Surprisingly when it comes to treatment, there is a lot more interest for MERS than for diagnostics (110 vs ). 
Also, it seems that the university of HongKong has been more heavily focused on diagnostics than treatment in that domain as they dropped to rank 13th in applications.
Private pharmaceutical companies such as [Intermune Inc](https://scrip.pharmaintelligence.informa.com/companies/199902106) (a division of Roche) are leading the applications count in this case.
Surprisingly there is a large number of patents owned by the US government for MERS treatment.


## Ventilators Patents : 

<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS93Ko4ToyIzhkRW82lDAHhEZmIs6od-Pq9nIke4tmdxWnyDEFyRJBMOr7SHKw3_HEpRQHrnTenOeTi/pubchart?oid=1574470958&amp;format=interactive"></iframe>

<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSEtB6Uuwvg5SDt2SuAUzwdzXfExkXBChwEBiBjvGxG_doEwiLnAq_c6yAtMsGsa9EUHu9S3xhPdfAb/pubchart?oid=941955487&amp;format=interactive"></iframe>

For ventilators, the number of patent applications is significantly higher than the MERS/SARS one. There were 8815 patents filled in 20years for an average of 440 a year. Patent filing is dominated by two german companies: Drager (7.7%) and Resmed (5.7%). Followed by Nellcor(5.5%), General Electric (3.4%), Covident (3.0%) and RIC(2.1%) making up a quarter of the total filling.

## Respirators and Surgical Masks Patents : 

<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vShFihuRAp43xlo8_xx5YH8EovhvkPCeLl_D2wcUWvh6T_8_DEbR3bpD2cOVt_Zqnk23X7NGL0ivsFd/pubchart?oid=1378721455&amp;format=interactive"></iframe>

<iframe width="610" height="380" seamless frameborder="0" scrolling="no"  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS4Ax3cK1oDZMcTiWLV8-8mKFyvs4hoWH1PDPvUzcZN-Ow_zAPWveLsBes0PNJJSgPIF3WiegMSbySp/pubchart?oid=1265692380&amp;format=interactive"></iframe>

As for masks, surprisingly, M3 (5.5%) is not the top patentee.
While still owning 5.5% of the fillings, the lion share is owned by Kimberly-Clark (13.5%), Avent (6.6%) and O&N Haylard (6.6%).
There were 4221 patents filling with an average of 211 a year over the past 20 years.

# Conclusion : 

We found that there is no one dominant entity, but a lot of companies, institutions, universities and governments own COVID-19 related patents. 
We found that for Masks and Respirators, the top 5 patents owners are filling 25% of the total patents over the past 20 years.
On the other hand, it was hard for the top 5 patents owners to break the 25% threshold when it comes to diagnostics and treatment.
This might be due to a more fragmented and/or a more competitive market when it comes to those aspects. 

However, there are only a few key companies and institution that have been consistently and actively applying for diagnostic and treatments patents over the past 20 years.
The University of HongKong and it is commercial arm Versitech Limited is leading the pack.
Furthermore, while these companies and institution only own a fraction of the total number of IP (a couple of percents, sometimes they push double-digit). They are the one that seems the best placed to benefit from the current pandemic.
They also potentially are the one capable of rapidly ramping up R&D using their prior expertise and existing resources to generate new diagnostic solution and treatment for the current pandemic.
Furthermore, with it, another spike of patents filling.

<!--End Main Container -->
