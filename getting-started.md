---
copyright:
  years: 1994, 2017
lastupdated: "2017-11-10"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Getting Started with DNS

The internet's Domain Name System (DNS) is a method of translating IP addresses that servers and routers recognize into user-friendly, given names called _domain names_ (for example, `ibm.com`).

While the concept of DNS is simple, managing and storing records for your various domains can become quite tedious if there isn’t a convenient method to do so.

IBM Cloud DNS offers customers a central location from which to view and manage their domains, by using our basic DNS management interface. It also gives users the option to manage reverse and secondary DNS in the same location, free of charge.

IBM Cloud also offers a suite of additional network tools for operations such as `ping`, `traceroute`, and `whois`. [Documentation is available at this link.](https://console.stage1.bluemix.net/docs/infrastructure/network-tools/getting-started.html#getting-started-with-network-tools)

## How it Works
At a basic level, {{site.data.keyword.BluSoftlayer_notm}} DNS functions similarly to any DNS management tool that you would use. You have the ability to interact with and edit existing DNS records, add new records, and update information about reverse DNS. The primary benefit of using {{site.data.keyword.BluSoftlayer_notm}} over another DNS management service or even managing it yourself is that you have a central, reliable location in which all of your data is stored.

As an additional service, {{site.data.keyword.BluSoftlayer_notm}} offers secondary DNS zones to our customers free of charge, allowing users to back up their primary DNS records in the event of data loss or node failure.

## Users interact with {{site.data.keyword.BluSoftlayer_notm}} DNS two ways.
Most users manage their primary, reverse and secondary DNS using our [Customer Portal ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://control.softlayer.com/). The Portal is our point and click interface to manage all things DNS.

You also have the option to use the IBM Cloud SoftLayer API (SLAPI) for DNS interactions. The functionality of the API compared to our Portal UI is almost identical. However, if you are editing DNS records in bulk, the Customer Portal provides bulking in sets up to 20, while the API offers more flexibility in that area. For more information about interacting with DNS using the SLAPI, refer to the Services page on the SLDN for the SLAPI.
