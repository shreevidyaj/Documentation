:orphan:

==========================================
Configuration Management Procedure
==========================================

**THIS PAGE IS CURRENTLY A WORK IN PROGRESS**


Configuration Management consists of four main actvities performed throughout the lifecycle of the program release and after its completion:

+------------------------+------------------------+----------------------------------------------------------------------------------------------------------------+
|Start of the Project    |     Identification     | Specification of all components (configuration items) and their inclusion in the CM system                     |
+------------------------+------------------------+----------------------------------------------------------------------------------------------------------------+
|Start of the Project    |     Control            | Management of each configuration item                                                                          |
+------------------------+------------------------+----------------------------------------------------------------------------------------------------------------+
|During the Project      |     Status             | Recording the current status of all configuration items in the CM system                                       |
+------------------------+------------------------+----------------------------------------------------------------------------------------------------------------+

The Configuration Management (CM) is a framework to establish and maintain the integrity of program-related work products and baselines throughout the lifecycle. This procedure documents the standardized repeatable methods/procedures, and helps guide the program team members in establishing a CM system -- tools and methods for the program.

+------------------------+---------------------------------------------------------------------------+
|Entry Criteria/Inputs:  | - A new program has been initiated/authorized and is in planning          |
+------------------------+---------------------------------------------------------------------------+
|Exit Criteria/Outputs:  | - Controlled and released configuration items and baselines               |
|                        | - Configuration status accounting                                         |
+------------------------+---------------------------------------------------------------------------+

**Steps**
---------

#. **Establish the CM system**
   
   -  CM Tools: Identify the CM tools used for the configuration management of the software lifecycle data, hardware and software tool components.
   
	  -  CM_File_Tool: General purpose file data capture and management tool (e.g., Git, SVN)
	  
	  -  Archive & Backup_Tool: Tool for storage or the released media, backup and restoring server data

   -  CM Servers: List the generic servers that host the configuration management tools and their configuration management data
   
	  -  CM server: Server used to host the CM_File_Tool and its back-end data repositories
	  
	  -  Release_Server: Server used to host the released media and its back-end data repositories
	   
   -  CM Methods: Describe the configuration methods used, in this case the file repository structure
  
   -  CM Responsibilities: Identify the responsibilities for all aspects of the CM tools, actvities including control, management and oversight.  
  
   -  CM Interfaces: Identify the interfaces to manage the CM activities
 
#. **Perform CM activities**
   
	- Configuration Identification: The CM Lead provides a description of configuration items to which the CM scope applies.  Items placed under CM include (but not limited to) Lifecycle Workproducts, and Development and Test Environment details
   
	  - Configuration Identification for Documentation (link TBD)
	
	  -  Configuration Identification for Development Data (e.g., development documentation, source code) (link TBD)
	
	  -  Configuration Identification for Verification Data ( e.g., peer review artifacts, test artifacts) (link TBD)
   
   -  Baseline and Traceability
   
	  -  Baseline (link TBD)
	 
	  -  Traceability (TBD)
	 
   -  Problem Reporting
   
   -  Change Management 
    
	  -  Change Control (i.e.,change impact anlaysis -- TBD)
	 
	  -  Change Review (TBD)
	 
   -  Configuration Status Accounting  
   
	  -  Baseline Status (TBD)
	  
	  -  Source Code Status (TBD)
	  
   -   Backup, Archive and Release  
   
	 -  Backup (TBD)
	 
	 -  Archive (TBD)
	  
	 -  Release (TBD)

#. **Manage CM data**
   
   -  The configuration management records are produced as required.



