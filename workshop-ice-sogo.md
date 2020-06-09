---
layout: default
title: ACM ICN 2020 Information-Centric Economic, Societal and Governance Workshop
short: ICE-SoGo 2020
group: Workshops

dates:
    - info: Paper submission deadline
      date: '<del>June 15,  2020</del> <span style="color: red">EXTENDED: July 6, 2020</span>'
    - info: Paper acceptance notification
      date: August 7, 2020

committees:
    - role: Workshop Co-Chairs
      people:
       - name:        Gareth Tyson
         affiliation: Queen Mary University of London
         homepage:    http://www.eecs.qmul.ac.uk/~tysong/
         email:       gareth.tyson@qmul.ac.uk

       - name:        Ignacio Castro
         affiliation: Queen Mary University of London
         homepage:    https://icastro.info/
         email:       i.castro@qmul.ac.uk

    - role: Technical Program Committee
      people:
       - name:        Yehia Elkhatib
         affiliation: Lancaster University
       - name:        Ruben Cuevas
         affiliation: UC3M
       - name:        Ian Brown
         affiliation: Research ICT Africa
       - name:        Dirk Kutscher
         affiliation: Emden University
       - name:        Andreas Mauthe
         affiliation: University of Koblenz and Landau
       - name:        Tuan Minh Pham
         affiliation: Phenikaa University
       - name:        Emanuele Giovannetti
         affiliation: Anglia Ruskin University
       - name:        Colin Perkins
         affiliation: Glasgow University
       - name:        Volker Stocker
         affiliation: TU Berlin
       - name:        Zoraida Frias
         affiliation: Universidad Politécnica de Madrid
       - name:        Niels ten Oever
         affiliation: University of Amsterdam

---
{%  comment %}


<!-- ### Workshop Program -->

<!-- {% include program-online.html type="workshop-ice-sogo" %} -->

{% endcomment %}

## {{ page.title }} ({{ page.short }})

### Call For Papers

The organizing committee invites you to contribute to the Information-Centric Economic, Societal and Governance Workshop (ICE-SoGo), held in conjunction with the ACM ICN'2020 Conference.
The workshop strives to offer a forum for discussion of all aspects related to the economic, societal and governance implications of deploying Information Centric concepts within the Internet.

The emergence and deployment of information-centricity on an Internet scale will have a dramatic impact on various economic, societal and governance aspects of Internet operations.
It will change how networks interconnect, how traffic is managed and charged, as well as how regulators approach governance matters.
Wider concerns related to things like data ownership, user privacy and law enforcement may also emerge.
The precise implications are difficult to predict, particularly as any deployments will involve multiple stakeholders with potentially divergent or even competing interests.
A lack of foresight on these matters may severely hamper the success of any future efforts.

The aim of ICE-SoGo is to foster discussions regarding economic, social and governance factors involved in deploying, operating and regulating information-centricity within the Internet.
The workshop encourages a broad interpretation of "information-centricity", and would welcome research related to Information Centric Networks (ICNs), Content Delivery Networks (CDNs), Cloud Storage, and even the Web more generally.
We refer to these collectively as Information-Centric Systems.

Submissions could, for example, cover how information-centricity may impact the concept of transit pricing; how it may trigger the emergence of new business models and stakeholders; the implications for law formulational and enforcement activities (e.g.
GDPR); and how these paradigms could disrupt existing practices.
Due to the nature of the topic, we would particularly welcome cross-disciplinary investigations.

We invite the submission of papers up to **six pages** in length (ACM SIGCOMM format), describing original research with both theoretical and applied contributions.
We also welcome position papers that explore the area more conceptually.
Note that we also welcome shorter paper submissions (below 6 pages) where appropriate and well justified.

#### Topics of Interest

Topics of interest include:

- Economic factors impacting Information Centric System deployment, operation and management;
- Regulation of Information Centric Systems;
- Law enforcement activities within Information Centric Systems (e.g., blocking of illegal content);
- Content moderation in Information Centric Systems;
- Trust management and data access control in Information Centric Systems;
- Economic fairness in Information Centric Systems;
- New economic models for Information Centric Systems;
- Resource, transit and information pricing;
- Deployment incentives for Information Centric Systems;
- Incentive-aware design of Information Centric Systems;
- Economic Models for an Internet of Open Content Replication;
- User Perspectives on Liability and Trust in an Internet of Secured Content Objects;
- Applications and Operations of Sessionless Open Content Distribution;
- Data Ownership, Access Rights, and Rights Management in Emerging Data-centric Domains (e.g., IoT).
- Open Content Distribution Infrastructure versus Internet Consolidation.

[Contact workshop co-chairs](mailto:{%
 for i in page.committees 
    %}{% if i.role == "Workshop Co-Chairs" 
        %}{% assign needComma=0 
        %}{% for p in i.people 
            %}{% if p.email and p.email != "" 
                %}{% if needComma==1 %},{% endif 
                %}{% assign needComma=1 
                %}{{ p.email 
            }}{% endif 
        %}{% endfor 
    %}{% endif 
%}{% endfor %}?subject=[{{ page.short }}]){: data-role="button" class="button" }.

#### Submission Instructions

Submissions must be original, unpublished work, and not under consideration at another conference or journal.
Submitted papers must be at most **six (6) pages** long, including all figures, tables, references, and appendices in [two-column ACM conference format](https://github.com/conference-websites/acmart-sigproc-template/) (10pt font, `sigconf` option for `acmart` style).
Papers must include authors names and affiliations for single-blind peer reviewing by the PC.
Authors of accepted papers are expected to present their papers at the workshop.

Link for the submissions will be posted soon.
Please submit your paper via [https://ice-sogo20.hotcrp.com/](https://ice-sogo20.hotcrp.com/).


### Important Dates

{% include dates2.html dates=page.dates %}

## Authors Take Note

**The official publication date is the date the proceedings are made available in the ACM Digital Library. This date may be up to *TWO WEEKS* prior to the first day of your conference. The official publication date affects the deadline for any patent filings related to published work.**

Due to uncertainty about international travel in the Fall of 2020, the Conference will offer a remote attendance/presentation opportunity.  Details are still being worked out, but further information will be made available as soon as possible.

### Committees

{% include committees.html committees=page.committees %}
