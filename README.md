# PegaTest
Improt both Automationframework and PegaAutomation Folder in to workspace and set chromedriver path in config property and run POM.xml for execution .

check all Important generic code in automationframework folder(Test Runner[which contains main method],test class utill for data provider code and reporting code ,Driver Manager for all driver)

Steps to Execute -

1- import both folder to workspace

2-right click POM.xml and go to run AS maven install (which install all jars and library) .

3-after that right click on PegaAutomation Folder and run as Maven Update to update all TestCase related folder .

Right click on Pom.xml of PegaDemoAutomation Folder and run As Maven Build(set goal as clean package exec:java thn click on apply and run) .
For testCases related code check package com.pega.test and for buisness flow sample check com.pega.datacreate package .
check input folder for testcase.xlsx file

check resources folder for congig properties file

Check test_execution_report3.html for report whichi is present inside test-output folder of pegaAutomation .

chnage chrome driver path under PegaDemoAutomation\src\main\resources and for any IE and firefox add key inside config.properties file .

