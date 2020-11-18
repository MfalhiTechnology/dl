---

copyright:
  years: 2020
lastupdated: "2020-10-27"

keywords:

subcollection: dl

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:DomainName: data-hd-keyref="DomainName"}
{:preview: .preview}
{:note: .note}
{:beta: .beta}
{:important: .important}
{:deprecated: .deprecated}
{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:term: .term}
{:generic: data-hd-programlang="generic"}
{:download: .download}
{:help: data-hd-content-type='help'}
{:support: data-reuse='support'}

# Equinix ordering considerations
{: #equinix}

After you create your Direct Link Connect order, follow these steps to create a connection for your Equinix service provider.

1. Log in to the Equinix Cloud Exchange (ECX) Fabric portal.

   * Navigate to [https://ecxfabric.equinix.com](https://ecxfabric.equinix.com).
   * Enter your username and password.
   * Click **Sign In**.   
1. In the Frequent Connections section, click the **IBM Cloud** tile.
1. In the **IBM Cloud Direct Link 2** profile, click **Create Connection**.

   ![Equinix ordering](/images/equinix-ibm-cloud-2.png "Equinix ordering")

1. In the Origin section, click **Port**.
1. Select a **Location**.
1. Select a **Destination**.
1. Click **Next**.

   ![Select Locations](/images/equinix-port.png "Select Locations")
   
1. On the Connections Details page, enter the connection information. For the IBM Cloud Account ID, enter the service key (for example, `114340xxx`) that was generated when you provisioned your direct link. This key can be found on the Direct Link details page.
   
   ![Connection Details](/images/equinix-connection-details.png "Connection Details")
   
1. Select a **Connection Speed**, then click **Next**.   
1. Review and click **Submit Your Order**.

The IBM Special Network Services (SNS) team receives your request and is able approve the connection in the buyer-side portal.
  
You can view your newly created virtual connection for Direct Link by going to **Connections**. The connection will be in a pending provisioning state (**Pending Provider VLAN**).

Accept the connection request by navigating to the IBM Cloud Direct Link page and clicking **Accept** from the Action menu.

The virtual connection shows as **Provisioned** in the Equinix Fabric portal.

The timeline for approval is within 24 hours.
{: note}