--------------------------------------------------------------------
README.TXT

Product       : IP2Location IP Country Redirection

Web Site      : http://www.ip2location.com
Email         : support@ip2location.com

(c) Copyright 2001-2017 IP2Location.com. All Rights Reserved.
---------------------------------------------------------------------


===========================================================================================================
PLEASE UNINSTALL ALL PREVIOUS VERSIONS OF THIS MODULE BEFORE INSTALLING THIS VERSION.
===========================================================================================================


+===================================-
| 1. Introduction
+===================================-

   Welcome to IP2Location.com.

   This module package contains the October 2014 IP2Location IP-Country 
   DB1 (IPv4+IPv6) LITE data for IP2Location database.
   
   For more information or to download the latest LITE DB:
   http://lite.ip2location.com/database-ip-country
   
   IP2Location IP Country Redirection ("IPCountryRedirectionVB") module 
   is designed for DotNetNuke community.

   IPCountryRedirectionVB module detects the web visitor's country 
   via their IP address and redirects them to another page or URL address 
   if that country has been blocked in the Country Configuration.

   IP2Location is a database solution to enable lookup of country, 
   region, city, latitude, longitude, ISP and domain name from IP 
   address by using IP2Location database.

   IP2Location has been used in many types of projects such as:

   1) select the geographically closest mirror
   2) analyze your web server logs to determine the countries
   3) credit card fraud detection
   4) software export controls
   5) display native language and currency 
   6) prevent password sharing and abuse of service 
   7) geotargeting in advertisement

   The database will be updated on a monthly basis for greater accuracy.

   Enjoy the products!

   - The IP2Location.com Team


+===================================-     
 | 2. Software Requirements
+===================================-

   1.	Visual Studio 2012 and above
   2.	VB.Net in ASP.Net 4.0 and above
   3.	MSSQL 2008 R2
   4.	DotNetNuke 7.0.2


+===================================-     
 | 3. IP2Location Installation Guide
+===================================-

   1.	Open the zip file.

   2.	Extract IP2LOCATION-LITE-DB1.IPV6.CSV and DB1-IPv6.FMT files into C: drive.

   3.	Start the DotNetNuke-based website.

   4.	Log in DotNetNuke portal as Host.

   5.	Select Install Module in Module Definition at Host tab.

   6.	Install the IPCountryRedirectionVB module package: 
	<drive>\<path>\IPCountryRedirectionVB_7.0.0_Install.zip.

   7.	After module installation complete, 
	select [IPCountryRedirectionVB] module to add on a page.

   8.	Select [Country Configuration] on the module to configure 
	which country to be redirect into which URL address.

   9.	On the Country Configuration Setting (Admin Settings), 
	select a country from the drop-down list and 
	specify the full URL address in the text box.

   10.	Click on the [Add] button to store the configuration.

   ** For custom database setup, please modify the script in 
   00.00.01.SqlDataProvider before installing the module in DotNetNuke portal.


+===================================-
| 4. Files in This Package
+===================================-

   File Name * : IP2LOCATION-LITE-DB1.IPV6.CSV
   Description : Complete database (IPv4+IPv6) in CSV (comma separated) ASCII text
                 format

   File Name * : DB1-IPv6.FMT
   Description : MSSQL database import format

   File Name   : README.txt
   Description : Read Me text file

   File Name   : DATA_LICENSE.txt
   Description : End-User License Agreement for use of IP2Location IP-Country [DB1] data

   File Name * : 00.00.01.SqlDataProvider
   Description : SQL Script for DotNetNuke IPCountryRedirectionVB 
		 module's database installation

   File Name * : UnInstall.sqldataprovider
   Description : SQL Script for DotNetNuke IPCountryRedirectionVB 
		 module's database uninstallation
   
   File Name * : Resources.zip\Edit.ascx
   Description : Admin Settings for IPCountryRedirectionVB module

   File Name * : Resources.zip\View.ascx
   Description : View Controls for IPCountryRedirectionVB module

   File Name * : IPCountryRedirectionVB.dnn
   Description : IPCountryRedirectionVB module's manifest file

   File Name * : bin\IPCountryRedirectionVB.dll
   Description : IPCountryRedirectionVB module's library


   * File name with asterisk (*) are important to be include in the package (zip file)
     for DotNetNuke Module installation.


+=========================- 
| 5. Technical Support
+=========================-     
   
   Any other problem and bugs please report at support@ip2location.com.