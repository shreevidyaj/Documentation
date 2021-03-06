:orphan:

==========================================
Configuration Management System Procedure
==========================================

**THIS PAGE IS CURRENTLY A WORK IN PROGRESS**

The configuration management is a framework to establish and maintain the integrity of program-related work products and baselines throughout the lifecycle. This procedure documents the standardized repeatable methods/procedures, and helps guide the program team members in establishing a CM system -- tools and methods for the program.

Configuration Management consists of four main actvities performed throughout the lifecycle of the program release and after its completion:

+------------------------+------------------------+------------------------------------------------------------------------------------------------------------------+
|Start of the Project    |     Identification     | - this is the specification of all components (configuration items) and their inclusion in the CM system         |
+------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
|Start of the Project    |     Control            | - this is the management of each configuration item                                                              |
+------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
|During the Project      |     Status             | - this recording the current status of all configuration items in the CM system and the maintenance information  |
+------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
|During the Project      |     Verification       | - this is the review and audit of the information contained in the CM system to ensure it is accurate            |
+------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+

A configuration identification is a component of configuration management consisting of selecting the program work products (configuration items for a product), assigning unique identifiers and recording their functional and physical characteristics. 

A configuration item is a collection of the program work products consisting of all required hardware, software, documentation, resources and other work products that comprise a baseline.

+------------------------+---------------------------------------------------------------------------+
|Entry Criteria/Inputs:  | - A new program has been initiated/authorized and is in planning          |
+------------------------+---------------------------------------------------------------------------+
|Exit Criteria/Outputs:  | - Controlled and released configuration items and baselines               |
|                        | - Configuration status accounting                                         |
|                        | - Configuration audit reports (verification of configuration records)     |
+------------------------+---------------------------------------------------------------------------+


**Steps**
---------

#. **Establlish the CM (Configuration Management) system
     - CM Tools  - Identify the CM tools used for the configuration management of the software lifecycle data, hardware and software tool components.
     - CM_File_Tool: General purpose file data capture and management tool ( e.g., Git, SVN)
	 - PR_Tool:  Problem report capture and management tool
	 - Archival/Backup_Tool: Tool for storage of the released media/for backup and restoring server data
	 - Release _Tool:  Tool used to release lifecycle data
	- CM Servers - List the generic servers that host the configuration management tools and their configuration management data
	 - CM server: Server used to host the CM_File_Tool and its back-end data repositories
	 - Release_Server: Server used to host the released media and its back-end data repositories
   - CM Methods - Describe the configuration methods used, in this case the file repository structure
   - CM Responsibilities - Identify the responsibilities for all aspects of the CM tools, actvities including control, management and oversight.  
   - CM Interfaces - Identify the interfaces to manage the CM activities
 
#. **Perform CM activities**
   - Identify the configuration items: The CM Lead provides a description of configuration items to which the CM scope applies.  Items placed under Configuration Management include (but not limited to):
     - Lifecycle Data/ work products 
	   - Requirements
       - Designs
       - Source code
       - Requirements-based tests
       - Test case codes, test scripts, test approach documents
       - Build rules 
       - Process and planning documentation
       - Review comments
       - Applicable standards documentation (e.g., requirements, design and coding standards)
       - Test results
       - Traceability links
       - SQA review and audit plans and records
     - Development and Test Environment details
	   	   
   - Configuration Identification for Documentation - See guidelines
   - Configuration Identification for Development Data (e.g., development documentation, source code) -  See guidelines 
   - Configuration Identification for Verification Data ( e.g., peer review artifacts, test artifacts) - See guidelines
   - Configuration Identification for Baseline and Traceability - See guidelines

#. **Manage CM data**

   -  The configuration management records are produced as required.



