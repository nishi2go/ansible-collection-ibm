
ibm_compute_vm_instance -- Configure IBM Cloud 'ibm_compute_vm_instance' resource
=================================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Create, update or destroy an IBM Cloud 'ibm_compute_vm_instance' resource

This module supports idempotency



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.10.0
- Terraform v0.12.20



Parameters
----------

  placement_group_name (False, str, None)
    The placement group name


  secondary_ip_count (False, int, None)
    None


  user_metadata (False, str, None)
    None


  hostname (False, str, None)
    None


  private_network_only (False, bool, False)
    None


  dedicated_host_name (False, str, None)
    None


  wait_time_minutes (False, int, 90)
    None


  tags (False, list, None)
    None


  flavor_key_name (False, str, None)
    Flavor key name used to provision vm.


  ipv6_enabled (False, bool, False)
    None


  ssh_key_ids (False, list, None)
    None


  post_install_script_uri (False, str, None)
    None


  placement_group_id (False, int, None)
    The placement group id


  bulk_vms (False, list, None)
    None


  os_reference_code (False, str, None)
    None


  network_speed (False, int, 100)
    None


  ipv6_static_enabled (False, bool, False)
    None


  notes (False, str, None)
    None


  dedicated_host_id (False, int, None)
    None


  hourly_billing (False, bool, True)
    None


  dedicated_acct_host_only (False, bool, None)
    None


  domain (False, str, None)
    None


  transient (False, bool, None)
    None


  public_bandwidth_unlimited (False, bool, False)
    None


  datacenter_choice (False, list, None)
    The user provided datacenter options


  image_id (False, int, None)
    None


  local_disk (False, bool, True)
    None


  evault (False, int, None)
    None


  id (False, str, None)
    (Required when updating or destroying existing resource) IBM Cloud Resource ID.


  state (False, any, available)
    State of resource


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

