
ibm_database_info -- Retrieve IBM Cloud 'ibm_database' resource
===============================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Retrieve an IBM Cloud 'ibm_database' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.5.3
- Terraform v0.12.20



Parameters
----------

  name (True, str, None)
    Resource instance name for example, my Database instance


  guid (False, str, None)
    Unique identifier of resource instance


  plan (False, str, None)
    The plan type of the Database instance


  members_memory_allocation_mb (False, int, None)
    Memory allocation required for cluster


  members_disk_allocation_mb (False, int, None)
    Disk allocation required for cluster


  resource_crn (False, str, None)
    The crn of the resource


  resource_status (False, str, None)
    The status of the resource


  resource_group_id (False, str, None)
    The id of the resource group in which the Database instance is present


  adminuser (False, str, None)
    The admin user id for the instance


  whitelist (False, list, None)
    None


  groups (False, list, None)
    None


  resource_controller_url (False, str, None)
    The URL of the IBM Cloud dashboard that can be used to explore and view details about the resource


  location (False, str, None)
    The location or the region in which the Database instance exists


  service (False, str, None)
    The name of the Cloud Internet database service


  version (False, str, None)
    The database version to provision if specified


  connectionstrings (False, list, None)
    None


  resource_name (False, str, None)
    The name of the resource


  status (False, str, None)
    The resource instance status


  adminpassword (False, str, None)
    The admin user id for the instance


  tags (False, list, None)
    None


  users (False, list, None)
    None


  resource_group_name (False, str, None)
    The resource group name in which resource is provisioned


  iaas_classic_username (False, any, None)
    (Required when generation = 1) The IBM Cloud Classic Infrastructure (SoftLayer) user name. This can also be provided via the environment variable 'IAAS_CLASSIC_USERNAME'.


  iaas_classic_api_key (False, any, None)
    (Required when generation = 1) The IBM Cloud Classic Infrastructure API key. This can also be provided via the environment variable 'IAAS_CLASSIC_API_KEY'.


  region (False, any, us-south)
    The IBM Cloud region where you want to create your resources. If this value is not specified, us-south is used by default. This can also be provided via the environment variable 'IC_REGION'.


  ibmcloud_api_key (True, any, None)
    The IBM Cloud API key to authenticate with the IBM Cloud platform. This can also be provided via the environment variable 'IC_API_KEY'.













Authors
~~~~~~~

- Jay Carman (@jaywcarman)

