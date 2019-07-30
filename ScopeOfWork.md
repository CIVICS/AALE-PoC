
# Automated Legal Entity Rapid Prototype


## _Draft Scope of Work and Project Plan_


## _July 17, 2019_

**This project scope and plan is proposed by the CIVICS.com AALE Tiger Team Privateers**



*   Project Principal: Dazza Greenwood
*   Project Legal Engineer: Bryan Wilson

**Initial Project Sponsor**

eCorp, Chad



---



[TOC]




---



## 


## Project Scope and Outcomes {#project-scope-and-outcomes}

The purpose of this privately funded rapid prototype project is create a working open source automated legal entity.  Key objectives include creating:



*   An automated process that results in a valid corporation or LLC business entity;
*   A simple and effective interface for creation, management and dissolution of said entity;
*   A live demonstration that tests the prototype against objective success metrics; and
*   A prototype that proves key concepts necessary to build a scalable production system.


## Project Timeline {#project-timeline}



*   Kick-Off: 7/30 
*   Launch: 8/8
*   Review: 9/30 (Tentative)
*   Handoff: 10/28 (Tentative)


## Project Deliverables {#project-deliverables}



*   GitHub Repo: [https://github.com/CIVICS/AALE-PoC](https://github.com/CIVICS/AALE-PoC) 
    *   Code (Open Source)
    *   Documentation (Creative Commons)
*   Working Prototype
    *   AWS?
*   Private Report
    *   Security and Privacy Considerations
    *   Draft Policies and Operating Procedures
    *   Key Engineering Challenges
    *   Strategic Opportunities
    *   Next Steps
*   Invitation to Join Phase 2


## Project Description {#project-description}

This project will follow an agile skunkworks development and discovery model, based on phases and stages of work, results, adaptation and delivery.  This rapid prototype is expected to require approximately three months or less to complete.  It is anticipated that this prototype will require approximately $15-20k to fund the research. 

This project will commence upon contract with an initial sponsorship of $5k and will seek additional funding from additional sponsors. However,  in the event no additional funding is acquired, this project will be managed to ensure delivery of some subset of usable deliverables are provided on a shorter time scale.

**COMMENTS:**



*   Question-  What are some potential use cases?   Does this run along the BBLLC route? 
*   Reply 
    *   The basic use case is to verifiably form a legally valid corporation or LLC in a jurisdiction of the United States through an automated process.  This scope is deliberately agnostic to the business activities the legal entity might engage in.  In principle the entity could engage in any activity and solving business transactions and other operations would be added as requirements or future larger scopes of work that build upon the base case of a valid legal entity.  
    *   Selection of the state or states for the prototype will be based on how easy it is to work with their online interface, fees charges and other costs, and capability to easily verify proof of existence online.  Some jurisdictions (eg Delaware) charge a fee for checking existence of a legal entity and other jurisdictions provide a free interface for such checks.
    *   The success metric would be to confirm proof of existence through an online lookup at an authoritative source.  Here is an example of a specific record of the existence of the Vermont BBLLC known as dOrg: [https://www.vtsosonline.com/online/BusinessInquire/BusinessInformation?businessID=357139](https://www.vtsosonline.com/online/BusinessInquire/BusinessInformation?businessID=357139) Here are examples of links to authoritative sources for proof of existence of a corporation or LLC in good standing: 

<table>
  <tr>
   <td>
<a href="http://arc-sos.state.al.us/CGI/CORPNAME.MBR/INPUT">Alabama</a>
<p>
<a href="https://myalaska.state.ak.us/business/soskb/CSearch.asp">Alaska</a>
<p>
<a href="http://starpas.azcc.gov/scripts/cgiip.exe/WService=wsbroker1/main.p">Arizona</a>
<p>
<a href="http://www.sosweb.state.ar.us/corps/index.html">Arkansas</a>
<p>
<a href="http://kepler.sos.ca.gov/">California</a>
<p>
<a href="http://www.sos.state.co.us/biz/BusinessEntityCriteriaExt.do">Colorado</a>
<p>
<a href="http://www.concord-sots.ct.gov/CONCORD/online?sn=InquiryServlet&eid=99">Connecticut</a>
<p>
<a href="http://www.corp.delaware.gov/directweb.shtml">Delaware</a>
<p>
<a href="https://business.dc.gov/research_business_info">D.C.</a>
<p>
<a href="http://www.sunbiz.org/search.html">Florida</a>
<p>
<a href="https://ecorp.sos.ga.gov/BusinessSearch">Georgia</a>
<p>
<a href="http://hbe.ehawaii.gov/documents/search.html;jsessionid=9148585DCF650B5F22DD05E291E3ECCF.liona">Hawaii</a>
<p>
<a href="http://www.accessidaho.org/public/sos/corp/search.html?SearchFormstep=crit">Idaho</a>
<p>
<a href="http://www.ilsos.gov/corporatellc/">Illinois</a>
<p>
<a href="https://secure.in.gov/sos/bus_service/online_corps/name_search.aspx">Indiana </a>
<p>
<a href="http://www.sos.state.ia.us/search/index.html">Iowa</a>
<p>
<a href="http://www.accesskansas.org/srv-corporations/index.do">Kansas</a>
   </td>
   <td> 
   </td>
   <td><a href="http://www.sos.ky.gov/Pages/default.aspx">Kentucky</a>
<p>
<a href="https://coraweb.sos.la.gov/CommercialSearch/CommercialSearch.aspx">Louisiana</a>
<p>
<a href="https://icrs.informe.org/nei-sos-icrs/ICRS?MainPage=x">Maine</a>
<p>
<a href="http://sdat.dat.maryland.gov/ucc-charter/Pages/CharterSearch/default.aspx">Maryland </a>
<p>
<a href="http://corp.sec.state.ma.us/corp/corpsearch/corpsearchinput.asp">Massachusetts</a>
<p>
<a href="http://www.dleg.state.mi.us/bcs_corp/sr_corp.asp">Michigan</a>
<p>
<a href="https://mblsportal.sos.state.mn.us/Business/Search">Minnesota</a>
<p>
<a href="https://corp.sos.ms.gov/corp/portal/c/page/corpBusinessIdSearch/portal.aspx?#clear=1">Mississippi</a>
<p>
<a href="https://www.sos.mo.gov/BusinessEntity/soskb/csearch.asp">Missouri</a>
<p>
<a href="http://app.mt.gov/bes/">Montana</a>
<p>
<a href="https://www.nebraska.gov/sos/corp/corpsearch.cgi">Nebraska</a>
<p>
<a href="https://nvsos.gov/sosentitysearch/">Nevada</a>
<p>
<a href="http://sos.nh.gov/nhbuslookup.aspx">New Hampshire</a>
<p>
<a href="https://www.njportal.com/DOR/businessrecords/">New Jersey</a>
<p>
<a href="https://portal.sos.state.nm.us/BFS/online/CorporationBusinessSearch">New Mexico</a>
<p>
<a href="https://www.dos.ny.gov/corps/bus_entity_search.html">New York</a>
<p>
<a href="http://www.secretary.state.nc.us/corporations/CSearch.aspx">North Carolina</a>
   </td>
   <td> 
   </td>
   <td><a href="http://www.nd.gov/sos/businessserv/registrations/business-search.html">North Dakota</a>
<p>
<a href="http://www2.sos.state.oh.us/portal/page?_pageid=35,58664,35_58678&_dad=portal&_schema=PORTAL">Ohio</a>
<p>
<a href="https://www.sos.ok.gov/corp/corpinquiryfind.aspx">Oklahoma</a>
<p>
<a href="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.login">Oregon</a>
<p>
<a href="https://www.corporations.pa.gov/search/corpsearch">Pennsylvania</a>
<p>
<a href="http://ucc.state.ri.us/CorpSearch/CorpSearchInput.asp">Rhode Island</a>
<p>
<a href="http://www.scsos.com/Search%20Business%20Filings">South Carolina </a>
<p>
<a href="http://apps.sd.gov/applications/st32cprs/soscorplookup.aspx">South Dakota</a>
<p>
<a href="http://www.tennesseeanytime.org/soscorp/">Tennessee</a>
<p>
<a href="http://ecpa.cpa.state.tx.us/coa/Index.html">Texas</a>
<p>
<a href="https://secure.utah.gov/uccsearch/uccs">Utah</a>
<p>
<a href="http://www.sec.state.vt.us/seek/corpbrow.htm">Vermont</a>
<p>
<a href="http://www.scc.virginia.gov/clk/bussrch.aspx">Virginia</a>
<p>
<a href="http://www.secstate.wa.gov/corps/corps_search.aspx">Washington</a>
<p>
<a href="http://www.wvsos.com/wvcorporations/verifylogon.asp">West Virginia</a>
<p>
<a href="https://www.wdfi.org/apps/CorpSearch/Search.aspx?">Wisconsin</a>
<p>
<a href="https://wyobiz.wy.gov/business/filingsearch.aspx">Wyoming</a>
   </td>
  </tr>
</table>



# Project Plan Pre-Launch Outline {#project-plan-pre-launch-outline}

**Phase I: Proof of Concept**



*   **Target: August/September**

Summary: Initial Requirements and Proof of Key Concepts

Overview:

_Atomized Functions for Key Junctures_



1. Define what we are doing so that the output is primarily a well-researched and verifiable definition of what the functional requirements are for building out code that would extend DocAssemble to form a legal entity and maintain it.
2. Define what the success metrics would be for the extent to which code achieves outcomes expected
3. Instead of a working prototype of the whole thing, define it so that we have a proof-of-concept of certain key junctures and capabilities of functions. For example, show data model of website, field match w/in docassemble, and show that from those inputs and these outputs here is what you get from chrome extension

Plan:



*   Identify the “target state” or states to create legal entity.  Default is [Delaware](https://community.lawyer/cl/communitylawyer/form-a-delaware-company-1).  Evaluate pro’s and con’s of using Series LLC’s.
*   Scope of final prototype: form, maintain and voluntarily dissolve a corporation or LLC under state law, verify existence and dissolution of entity using authoritative state data and create interface and process easy enough for one person small business and easy to integrate with other automated business process 
    *   At a high level, provide a design architecture for how other business systems could plug this prototype in as a module, including the data model, data flow and API approach.  
*   Create a public website
*   Manually go through and carefully document the process of forming a legal entity and getting tax id at federal and state levels
*   Accurately and completely account for every action and process needed in the form of a DocAssemble interview list
*   Identify the gap between what [DocAssemble](https://community.lawyer/cl/communitylawyer/form-a-delaware-company-1) does natively and what is needed to complete the entire process and achieve the result of a valid legal entity with tax ID in order to generate the functional and other requirements and good candidate technologies for completing the needed actions.
*   Generate some proof of concept implementations of DocAssemble and other good candidate technologies (eg maybe[ Chrome Extension](https://github.com/form-o-fill/form-o-fill-chrome-extension and https://form-o-fill.github.io/tutorial) or [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/), etc, etc) of key functions needed for a working prototype.
*   Identify an initial framework for what parts of this system should assume and require humans in the loop or in the drivers seat and what parts of this system should assume fully automated processes that humans are not expected to “review or approve”.

Notes:

**_Chad can come to Boston for a day in Sept to sync up and get demo and provide review._**

Start by manually creating a corporation and carefully document a super-set interview question set of everything people need to know/write/send in order to form a corp/llc and get tax ID. This will show us:



*   What “common data elements” exist and can be re-used, and
*   What the “gap” is between what DocAssemble can do and what is missing in order to automate a integrated/single system/process for creating/maintaining a legal entity.

**Phase II: Integrated Prototype**



*   **Target: October/November**

Summary: Build and Test Integrated Prototype

Overview:

**Phase III: Deploy Initial Production System**



*   **Target: January/February**

Summary: Deploy Version 1 in the Wild
