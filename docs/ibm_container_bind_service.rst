
ibm_container_bind_service -- Configure IBM Cloud 'ibm_container_bind_service' resource
=======================================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Create, update or destroy an IBM Cloud 'ibm_container_bind_service' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.5.3
- Terraform v0.12.20



Parameters
----------

  region (False, str, None)
    The cluster region


  tags (False, list, None)
    List of tags for the resource


  key (False, str, None)
    Key info


  service_instance_name (False, str, None)
    serivice instance name


  account_guid (False, str, None)
    The bluemix account guid this cluster belongs to


  cluster_name_id (False, str, None)
    (Required for new resource) Cluster name or ID


  org_guid (False, str, None)
    The bluemix organization guid this cluster belongs to


  space_guid (False, str, None)
    The bluemix space guid this cluster belongs to


  role (False, str, None)
    Role info


  namespace_id (False, str, None)
    (Required for new resource) namespace ID


  resource_group_id (False, str, None)
    ID of the resource group.


  service_instance_id (False, str, None)
    Service instance ID


  id (False, str, None)
    (Required when updating or destroying existing resource) IBM Cloud Resource ID.


  state (False, any, available)
    State of resource


  ibmcloud_api_key (True, any, None)
    The IBM Cloud API key to authenticate with the IBM Cloud platform. This can also be provided via the environment variable 'IC_API_KEY'.













Authors
~~~~~~~

- Jay Carman (@jaywcarman)

