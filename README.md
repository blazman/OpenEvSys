[OpenEvSys](http://www.openevsys.org/): a web application for documenting human rights violations 
=================
 
Copyright, licence and disclaimer
-----------

OpenEvSys is a database for managing information about human rights violations. OpenEvSys is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
OpenEvSys is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Affero General Public License for more details.
You should have received a copy of the GNU Affero General Public License along with this program. If you didn't, head here: 
http://www.gnu.org/licenses/. 

Some parts of OpenEvSys are included in the software package through Free Software Licenses enabling their redistribution, modification and inclusion in new works such as OpenEvSys. Copyright of these components is retained by the owners. The terms of their use are indicated clearly in the source files. 

Technical requirements, download and install
----------

You will need the following installed on your local PC or server:

- Apache2 or PHP5 compatible web server.
- PHP 5 or latest
- MySQL 5 or latest
- PHP5-mysql driver
- php-mbstring module

Instructions on how to install OpenEvSys are contained in the file called "INSTALL.txt".


Features
----------

* **A free, open source web application for managing information about human rights violations**:

* OpenEvSys is used exclusively through an Internet browser.
* With ease OpenEvSys can be set up to work on a server over the Internet, from a computer in a closed office network, or simply on a single personal computer. 
* Additional layers of access control and security commonplace in safeguarding a web server are easily layered onto the OpenEvSys web application where necessary
* HURIDOCS has released OpenEvSys for use using the Affero General Public License v.3, a free software license, guaranteeing others the right to scrutinise, distribute and improve OpenEvSys. This means others can benefit from the public money spent on developing OpenEvSys.
* OpenEvSys is also a platform.  It is built using its own flexible framework - a set of reusable components in the php programming language , that can be used by software developers to expand the system, or even build others, very quickly. OpenEvSys is an object oriented MVC framework, embodying currently popular/good practice in the design of web applications. 

* **A complete implementation of the HURIDOCS "Events" approach for documenting human rights violations**:

* OpenEvSys implements the HURIDOCS "Events" model, a way of capturing the complexity of human  rights  violations. This is based on the HURIDOCS Events Standard Formats: a set of 9 different types of form  containing over 200 data fields to describe Persons, the roles they play in 
human rights violations (Victims, Perpetrators, Sources of information, Intervening Parties),  and the many relationships between them;
* The HURIDOCS Micro-Thesauri: 48 detailed controlled vocabularies (drawn from the international  human rights legal framework)  which can be used to describe types of act, methods of violence used, the human rights affected, the relevant international legal instruments, types of perpetrator, characteristics of victims and many other aspects of a human rights event;
* All data fields and Micro-Thesauri are directly configurable through the OpenEvSys administration interface:
-- Existing data fields can be made mandatory, renamed, re-ordered, hidden, deleted and translated into other languages.
-- New data fields of different types, including dates and text fields, can be added to any of the  Events Standard Formats from the OpenEvSys administration interface.
-- All Micro-Thesauri can be removed, added to, updated, completely re-purposed and interactively translated directly within OpenEvSys.
-- HURIDOCS Glossary text is accessible from all fields in the standard Events Standard Formats, giving users instant but unobtrusive access to guidance about when and how to use each field.

- Clarifying notes can be added to any field, enabling users to add very fine levels of detail, and resolve data ambiguities where required. 

* **A new "Document" Standard Format has been included in OpenEvSys to enable the  management of source material and digital file attachments within the OpenEvSys database**:

* A Document comprises a metadata record and an optional electronic file upload in any file format;
* A Document can be linked to many different records, and a single record can link to many different Documents: this enables users to associate original evidence like witness testimony, photographs or audio/video recordings directly with the record(s) they support. 

* **OpenEvSys is a multi-user system with a simple access control/permission and audit model**: 

* Many different users can work on OpenEvSys at once making it practical for larger and distributed organisations to integrate a documentation system into their work.
* User accounts and passwords can be created and disabled by a system administrator.
* "Roles" having different levels of access to the features of OpenEvSys can be defined eg. complete access, access only to Persons, only to Events, etc Users are assigned different roles.
* Roles can be given different degrees of control over all records in OpenEvSys, including complete control, read-only, create but not delete, update but not delete, etc
* OpenEvSys users have control over their passwords and can associate personal information with their accounts if required by their organisation. 
* Access to specific Events (and records linked to that Event) can be restricted by role, creating a robust way to conceal and compartmentalise sensitive information where necessary.
* A "lite" auditing feature records the actions that all users perform on records, automatically time-stamping when records are created, linked with each other, updated or deleted by users. 

 
* **An interface focussed firmly on making the most common, routine tasks very easy to perform**: 

* A clean and spacious, easy to use  HTML and discrete JavaScript interface, giving the feel of a thoughtfully-designed modern website. 
* OpenEvSys uses the near ubiquitous conventions of the Internet browser, so it feel and behaves in a very predictable, familiar way. 
* OpenEvsys's rich functions and features are progressively revealed relevant to the task being performed by the user, rather than being immediately on show at all times. 
* Workflows built into OpenEvSys simplify the creation of complex links between records eg.  OpenEvSys walks the user through the creation of a violation by creating the Victim record, then the Act record, the Perpetrator record(s) and the Involvement record(s). The user will never lose their place when entering data. 
* Context-sensitive keyboard short cuts to quickly access the main areas and functions of OpenEvSys eg. Go to Events, View Event, create Event, Event Event, etc.
* A greatly expanded, completely configurable record "browse" area for Persons, Events and Documents, allowing users to dive into their data, and quickly slice it up to find any record:
* "Browse" areas display summary information about records in a row-column form like a spreadsheet eg.
-- Rows are filterable and sortable by any values in any column, and the user can choose how many  results to display on the page. 
-- Browse area columns can be added to, removed from and re-ordered within browse areas as needed by the user.
* Informative and prominent alerts and error messages highlight errors, permanent actions or unexpected system behaviour. The user is rarely "dumped" without an explanation of what to do next.

* **Basic analytical and reporting capabilities**

* Users can search in OpenEvSys on single formats (eg. Event, Act, Involvement), and some common combinations of formats (eg. Victims = Person  + Act).
* Users can decide what fields to include in a search, and what fields to use to display the search results (the descriptors).
* A dynamic views of search results are used to provide a different view of search results eg. a search for any Events in which the Right to Life was violated can be changed to show just Victims, or the Perpetrators within those Events. A search on Victim can be changed to show only the Perpetrators.
* Any set of results in OpenEvsys can be exported and saved in the common Excel and .csv format  for further analysis in a spreadsheet or other tool.
* Any query can be saved and later re-run by other users of the system.
* Search fields (including those in the record browse areas) accept "fuzzy", incomplete partial  values of any sort. OpenEvSys makes use of the soundex algorithm to detect similar sounding words in searches (English language only).
* All Events can be printed in their entirety, including all linking formats and associated  entities eg. Persons, Acts, Chain of Events, etc.
