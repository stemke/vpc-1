---

copyright:
  years: 2018, 2019
lastupdated: "2019-11-03"

keywords: virtual server instances, VSI, planning, best practices

subcollection: vpc

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:table: .aria-labeledby="caption"}

# Planning for instances
{: #vsi_best_practices}

When you're planning to provision virtual server instances for {{site.data.keyword.vpc_short}}, you might find this configuration checklist helpful to get the most out of your deployment.
{:shortdesc}

Before you get started, make sure that you [created a VPC](/docs/vpc?topic=vpc-getting-started#getting-started).
{:important}

## Planning for provisioning instances
{: #planning-for-provisioning-instances}
After you have a VPC available, consider the following before you provision your instance.

|        Considerations|
|-------------------|
|__ Make sure your account has the required user permissions. If you have authorization as an editor or admin on a VPC resource, then you also inherit authorization to create, delete, and modify virtual server instances within that virtual private cloud.|
|__ Check your [account limits](/docs/vpc?topic=vpc-quotas#virtual-server-instances) for concurrent instances. |
|__ Make sure your [SSH key](/docs/vpc?topic=vpc-ssh-keys#ssh-keys) is available.
|__ Determine what region and zone to select.|
|__ Determine which subnets you want the instance to connect to.|
|__ Consider the popular [profile options](/docs/vpc?topic=vpc-profiles#profiles) of vCPU and RAM combinations for your workload. Profiles contain preconfigured instances that are ready to use in a matter of minutes. It's important to ensure that your instances have the necessary resources to keep your workloads and your environment up and running.|
|__ Determine what operating system image to select for your instance. You can choose among the current stock images or specify your own custom image. |
|__ Make sure you have a unique name for the instance. If you have a method to naming virtual server instances, it's much easier to filter and search on them later. |
|__ Determine how many secondary storage volumes you need. |
|__ Determine how many network interfaces you need and which security group to attach to each interface.|
{: caption="Table 1. Checklist for planning to provision instances" caption-side="top"}

## Next steps
{: #next-create-instance}
When you're ready to get started, see the following tutorials:
 * [Using the {{site.data.keyword.cloud_notm}} console to create VPC resources](/docs/vpc?topic=vpc-creating-a-vpc-using-the-ibm-cloud-console)
 * [Using the CLI to create VPC resources](/docs/vpc?topic=vpc-creating-a-vpc-using-cli)
 * [Using the REST APIs to create VPC resources](/docs/vpc?topic=vpc-creating-a-vpc-using-the-rest-apis)
