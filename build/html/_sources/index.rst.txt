.. PickleC2-ReadTheDocs documentation master file, created by
   sphinx-quickstart on Sat Jul 10 09:50:36 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to PickleC2's documentation!
================================================

Overview 
===================================

PickleC2 is a simple C2 framework written in python3 used to help the community in Penetration Testers in their red teaming engagements.  

PickleC2 has the ability to import your own PowerShell module for Post-Exploitation and Lateral Movement or automate the process.  


Features
=================================

There is a one implant for the beta version which is powershell.

1. PickleC2 is fully encrypted communications, protecting the confidentiality and integrity of the C2 traffic even when communicating over HTTP.
2. PickleC2 can handle multiple listeners and implants with no issues
3. PickleC2 supports anyone who would like to add his own PowerShell Module


Future Features
==========================

In the up coming updates pickle will support:

1. Go Implant
2. Powershell-Less Implant that don't use System.Management.Automation.dll.
3. Malleable C2 Profile will be supported.
4. HTTPS communications will be supported. NOTE: Even HTTP communications is fully encrypted.

Install
============================  

PickleC2 is a opensource can be found on Github. 
PickleC2 is only supported for linux for now and you can download it through https://github.com/xRET2pwn/PickleC2





.. toctree::
   :maxdepth: 2
   :caption: Contents:

   installation
   Usage
   Modules
   FAQ



.. raw:: html
   :file: buymeacoffe.html