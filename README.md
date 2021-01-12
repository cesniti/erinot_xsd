# Electronic Reporting (ERI) 
## ERINOT xsd
The Repository keeps track of the ERINOT XSD, including official releases and change requests (feature branches).

This repository aims to record and keep track of versions of technical documents related the temporary Working group CESNI/TI/ERI.

The technical documents (XSD Schema) reflects the ERI Standards of the european commission : [COMMISSION IMPLEMENTING REGULATION (EU) 2019/1744 of 17 September 2019 on technical specifications for electronic ship reporting in inland navigation and repealing Regulation (EU) No 164/2010](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32019R1744&from=EN)

The future Standard ES-RIS 2021/1 is buddling the Standard related to technical services and will be available in 2021 on the https://cesni.eu website.
The future Standard ES-RIS 2023/3 is in progress and *could* include technical files such as XSD fileS.

## Getting started
All official releases of the ERINOT XSD are tagged with their [release number](https://github.com/cesniti/erinot_xsd/releases)

The next coming release is the release 1.3.

## When and how are the new XSD released ? 

After each **release** the documents will be stored to the section of the ERI documentation on the https://ris.cesni.eu/ website.
To make the file available on a fixed url (needed for some application, the CESNI secretariat publishes each release and upload the necessary files to the [the CESNI/TI ASSETS folder](https//ris.cesni.eu/_assets/).

## How to Contribute ? 

All pull requests based on discussions and conclusions at CESNI/TI are most welcome.

You can : 
1. clone this repository in a local folder
2. create a branch to store your changes and improvements
3. provide the aim of the improvement filing out the commit messages
4. Once ready and cleaned your branch commits, you can submit your changes by means of a pull request. 

The pull request will be examined during the RIS WEEK by the temporary Working Group CESNI/TI/ERI by illustrating it into a change request.
Once approved the pull request will be included(merged) into the develop branch by CESNI/TI Secretariat.

If you are not familiar with this process you can contact the [CESNI/TI Secretariat](mailto:ti_cesni@cesni.eu)

## What are the branches ? 

There are 4 types of branches in each repo :
- The main branch that contains only the fully validated (by CESNI) editions
- The development branch that gather all the development work after it has been validated at the CESNI/TI/ERI level
-The release branch that is derived from the development branch to prepare the validation process to merge with the main branch
- The features branches (typically one by CR) that derive from the development branch and is used to split the work in small bits

## What are the rules of access and control of the repository ? 

Rules of access of the repository are the following : 
- Merging into the main branch is protected and can be done by the secretariat only, upon decision of CESNI
- Merging into the development branch is protected and can be done by the secretariat only, upon decision of the chair of CESNI/TI/ERI
- No merging into release branch, but this branch is also managed by the secretariat in the validation process of CESNI/TI and CESNI
- No merging into the current feature branches
- However, anybody can “create” features branches and the pull request it into the development branch (this is controlled by the CESNI/TI secretariat)

## The secretariat needs to make a few technical check before merging :
- Ensure that a proper documentation of the work has been done
- Ensure that the resulting XSD file is valid (from a syntax point of view)
- Ensure that the validation has been done (by the correct body) before it is merged

## Edition advises 
- The XSD file itself should only contains a “light” documentation in the header, the “comments” should be most part of the commit messages
