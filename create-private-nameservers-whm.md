---
copyright:
  years: 1994, 2017
lastupdated: "2017-10-11"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Create Private Nameservers in cPanel/WHM

Using the cPanel/WHM product, you can create private nameservers at any time. Private nameservers allow the nameservers associated with a website (for example, `www.yourdomain.com`) to display the website's nameserver (for example, `ns1.yourdomain.com`) instead of the nameserver associated with the web host for the website (for example `ns1.webhostdomain.com`). Adding a private nameserver to a domain also opens up additional options for DNS management within cPanel/WHM. Follow the steps in this article to create a private nameserver. If issues arise during or after the execution of this procedure, please [open a ticket](/general/create-ticket.html).

## Name the Nameserver

* Log in to WHM on your server at the following URL: http://xx.xx.xx.xx:2086.
* Select **Basic cPanel/WHM Setup** from the **Server Configuration** menu.
* Enter the desired nameserver hostname(s) in one or more of the following fields:
  * Primary Nameserver
  * Secondary Nameserver
  * Tertiary Nameserver
  * Quaternary Nameserver
* Select the **Save** button.

## Create a Zone File for the Domain

* Select **Add a DNS Zone** from the **DNS Functions** menu.
* Enter the **IP address** for the domain in the **Ip** field.
* Enter the **domain name** in the **Domain** field.

**Note:** Alternately, a Domain Account may be created with the [Create an Account](http://docs.cpanel.net/twiki/bin/view/AllDocumentation/WHMDocs/CreateAccount) guide in cPanel's WHM documentation.

## Assign an IP to the Nameserver

* Select **Nameserver IPs** from the **Network Setup** menu.
* Enter the first **nameserver name** in the **Nameserver** field.
* Select the **Assign** button.
* Repeat the steps above for each nameserver.

## Set Up the Nameserver

* Select **Nameserver Setup** from the **Service Configuration** menu.
* Select the **Proceed** button on the pop-up message.
