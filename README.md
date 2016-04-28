# History of phpOpenbiz

phpOpenbiz Framework also only called Openbiz Framework is great PHP Application Framework created by Rocky Swen (@rockycubi) since 2003. This framework focus on build tools to develop business application fast and easy.

"Want to build a data centric business application without dirty code - PhpOpenbiz (Openbiz) is the solution! OpenBiz is a PHP application framework for professional IT developers and consultants to build web-based enterprise applications."

But now, this framework is dead. phpOpenbiz no long maintained. Last commit by Rocky Swen on Jun 14, 2014 (r5528), after that, Agus SUhartono commit litle bugfix on May 8, 2015 (r5529).

NOTE : 
Openbiz LLC, lead by Jixian Wang, try to port this project to JavaScript. First initial commit by Jixian on  Feb 4, 2013. And the last commit on Jan 4, 2015. This project also dead? We don't know.

Now, Agus Suhartono (@agussuhartono) that join as phpOpenbiz contributor since 2009, trying to revive this project. At least maintain this project from extinction. 

This document contain history of phpOpenbiz that we are can collect.

Repositoies
-----------
https://github.com/phpopenbiz
https://github.com/openbiz (JavaScript)
https://github.com/rockycubi
https://code.google.com/archive/p/openbiz-cubi
https://sourceforge.net/projects/bigchef/


Websites :
----------
https://web.archive.org/web/20121101065618/http://www.phpopenbiz.org/home/developer/cubi.php
https://web.archive.org/web/20120920012847/http://www.phpopenbiz.org/jim/
https://web.archive.org/web/20070216011157/http://www.phpopenbiz.org/jim/
https://web.archive.org/web/20051103053400/http://www.phpopenbiz.org/document/release.html
https://web.archive.org/web/20051103051156/http://www.phpopenbiz.org/document/


##Timeline

Following old information we get from Archive.org 

### 2016-04-28 
Agus Suhartono trying to revive this project on Github



### November 3 2005
Oldes phpOpenbiz website and forum
- Website : https://web.archive.org/web/20051103051156/http://www.phpopenbiz.org/document/
- Forum : https://web.archive.org/web/20051103034255/http://p2.forumforfree.com/obhelp.html




From [https://web.archive.org/web/20051103053400/http://www.phpopenbiz.org/document/release.html]

### Oct 26 2005
#### Openbiz 2.0 is released. Openbiz eclipse plugin 0.9.2 is released with 2.0. 
Openbiz 2.0 includes mainly bug fixes and more details in openbiz manual. 

### Sep 29 2005 
#### Openbiz 2.0 RC2 is released. 
RC2 still works with Openbiz Eclipse plugin 0.9.1. Changs of Openbiz 2.0 RC2 from 2.0 RC1:

* New project structure to separate openbiz core library and applications
 - Openbiz core library
 - demo application
 - Openbiz developers need to reorganize your application specific code
* More bugs fixed


### Sep 15 2005
#### Openbiz 2.0 RC1 is released. 
RC1 still works with Openbiz Eclipse plugin 0.9.1. Changs of Openbiz 2.0 RC1 from 2.0 beta 2:

* New security model is added in openbiz architecture
 - User authentication
 - Role-based view access control
 - Attribute-based data access control
* More plugin services included in the package
* To work this release with Openbiz Eclipse plugin 0.9.1, please download BizDataObjProfile.xml and put it under org.openbiz.metadata_0.9.1/config directory.


### Aug 22 2005 
#### Openbiz 2.0 beta 2 is released. 
Beta 2 still works with Openbiz Eclipse plugin 0.9.1. Changs of Openbiz 2.0 beta 2 from 2.0 beta:

* Fix bugs of running openbiz on Unix/Linux OS.
* Fix bug of binding dynamic list (Table column) to comboBox


### Aug 08 2005
#### Openbiz 2.0 beta is released. 
Changs of Openbiz 2.0 beta from 2.0 alpha:

* Integrate Openbiz Eclipse Designer in the release
* Fix bugs on both Openbiz Framwork and Designer
* Demo redone - include web calendar



### July 24 2005
#### Openbiz Eclipse plugin 0.9.0 is released. 
See manual here [https://web.archive.org/web/20060907215647/http://www.phpopenbiz.org/document/designTool.html]. Important features include:

* Wizards for creating metadata files
* GUI interface for editing metadata files
* Possible to integrate with PHPEclipse


### May 31 2005 
#### Openbiz 2.0 alpha is released. 
Important features in Openbiz 2.0 alpha:

* Complete Object Relational Database mapping (ORM)
 - Support mapping M-1, 1-M, M-M table relationship to BizDataObj
 - Support aggregating tables column into a BizDataObj by join
* Fully support PHP5 new object-oriented model
* Metadata declaration file enhancement
* Include Web-Calendar as a shared component

### February 02 2005
#### Openbiz 1.2 beta is released. 
Important features in Openbiz 1.2:

* Fully support PHP5. Cannot run on PHP4 engine.
* A new BizSystem class to provide a common application infrastructure layer
* Most code is rewritten and reorganized to present better classed hierarchy.
* Keep the same functionalities and metadata as 1.1.1. Upgrading is trivial work.

#### Openbiz 1.1.1 fix pack is released. 
It is mainly bug-fixing release. Please upzip the php files under openbiz_root/bin directory.

### October 02 2004
Openbiz 1.1.1 is released. Important changes from Openbiz 1.1:

* Metadata inheritance.
  - Allow BizObj and BizForm metadata files inherit from parent object's metadata.
  - Increase development productivity, make application management easy.
* Provide no cache option for BizObj query.
    - Lower the BizObj memory usage for most navigation only views.
* HTML ComboBox and table column binding
* Composite key support in BizObj

### August 06 2004
Openbiz 1.1 is released. Important changes from Openbiz 1.1 beta:

- Allow users to specify 3rd party package directories in sysheader.inc file.
  - This makes easy resource sharing and more efficient opcode caching. Now support ADODB, SMARTY, FPDF, JPGRAPH.
- Introduce chartService as plug-in service. 
  - chartService renders chart based on the chart xml file. Support Bar, Line, Pie and combination charts.
- Support more flexible queries on BizForm
  - Can query with >, >=, <, <=, !=, = symbols and AND, OR logic connections
- Calendar and timestamp picker improvement
  - More compact and easier configuration by changing style sheet file and variables definitions

Download Openbiz 1.1 patch [link dead] to fix smarty setting and AccessValidate errors. Download Openbiz 1.1 composite key enhancement [link dead] to support composite keys. 

### July 04 2004 
Openbiz 1.1 beta is released. Jumping from 1.02 beta to 1.1 beta is due to the significant changes:

- All metadata files are organized by packages so that metadata files for big application can be stored in different directories. 
- Easy plug-in service interface to invoke customer-specified functions.
- Long-expected PDF report and Excel export support are added as plug-in services.

### June 14 2004
Openbiz 1.02 beta is released. More efficient session management is introduced to reduce the session file size (save memory usage if you map session directory to memory). Building multiple-database application is supported.

### May 22 2004
Openbiz 1.01 is released. More flexibility is added by introducing OtherSQLRule and support SQL functions in BizObj. View access control is easier to use than before. To answer customers questions, a FAQ page is available on Openbiz website.

### April 24 2004
Openbiz 1.01RC is released. Compiled config files feature is introduced.

Every *.xml file is compiled to *.cmp file which is a serialized array, reading config file is just unserializing *.cmp file instead of parsing it with domxml. This feature is very important to use openbiz on a web-hosting site where you don't have permission to enable php extensions. Meanwhile loading the *.cmp config file is 50% faster than parsing it with domxml. But in order to use Design Studio, you still need enable domxml php extension.

### April 18 2004
2 main new features are added in B10110 release.

- Openbiz windows installer works with AppServ (install Appache + PHP). It can help you install source code + Demo database and enable mmcache + domxml extensions.
- BizFormTree class is new to present the tree hierarchy of a database table. Please see maual for detail. Meanwhile demo is rewritten to cover more features.
- To fix a Mozilla/Netscape bug, please download the patch as well, copy the clientUtil.js to the root of openbiz.

### February 29 2004
Some BizForm improvement added in B10109 to give more convenience and flexibility in writing templates. Please view change log for detail. Updating BizForm and BizObj xml schema is needed. To see the demo, please reapply gendb.sql to demo database. Design Studio performance issue is solved in B10109.

### OpenBiz 1.01 B10108  (Date unknown)
Customerizable view access control interface is also available in B10108. Support 3 types of permission - No Access, Read, Write. Please read manual for details. *Need upgrade BizForm schema.

### OpenBiz 1.01 B10107 (Date unknown)
Supports common HTML elements, please check Section 5.6 "Present data with various HTML elements" in manual page. Please download the gendb.sql to get the demo work. *Need upgrade BizForm and BizView Xml schema. 

### OpenBiz 1.01 B10105 (Date unknown)
Add BizField Type, Format and validation in OpenBiz 1.01 B10105. Schema change on BizObj, please check Section 3.5 "Upgrade configuration xml files when openbiz xml schema changes" in manual page. *Need upgrade BizObj Xml schema

### OpenBiz 1.01 B10102 (Date unknown)
XMLHTTP is used to make RPC call since OpenBiz 1.01 B10102, RPC no longer goes through a hidden iframe. Support IE 5+, Mozilla 1.x and Netscape 7.x browsers.

### OpenBiz 1.01 B10101 (Date unknown)
OpenBiz Design Studio is included in the package. Your configuration process will be enjoyable and error-proof. Please see Tutorial to understand how to use Design Studio. After install the package, open Design.htm in browser. In unix, make sure your metadata directory has write permission open for web clients. 


