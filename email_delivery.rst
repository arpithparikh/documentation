.. _email_delivery:

Email Delivery
==============

Handshake maintains highly reputable emailing domains to ensure that emails are delivered. However, email delivery can sometimes fail due to the various systems in between Handshake and students which are designed to prevent email abuse. In order to maintain high deliverability, Handshake monitors and acts on spam scores, blacklisting, IP throttling and more.


Email Delivery Guidelines
-------------------------

Google
######

We recommend whitelisting all IP addresses in your Google Apps Console for Gmail as this will ensure no messages are flagged as spam. This can be accomplished by following this: https://support.google.com/a/answer/60751?hl=en
There are also some general guidelines for bulk emailing recommended by Google if you are mass emailing using Handshake: https://support.google.com/mail/answer/81126

Microsoft
#########

We recommend whitelisting all IP addresses in your Exchange or Office 365 admin portals. This can be accomplished by following this: https://technet.microsoft.com/en-us/library/jj200718(v=exchg.150).aspx 

Whitelisting
------------

Handshake sends a large amount of email notifications and depending on your school's use of the mass email feature, you should consider whitelisting handshake for more reliable email delivery. Whitelisting can better assure that emails sent to students and staff are received.

Whitelist by Domain
###################

Domain:  ``*.joinhandshake.com``

Whitelist by IP
###############

We send notifications from a dedicated set of IP addresses, you can whitelist these.

Regular Notifications are sent from: (notifications.joinhandshake.com)

* ``192.237.158.52``
* ``192.237.159.133``

Mass emails are sent from (mail.joinhandshake.com)

* ``192.237.159.131``
* ``192.237.159.132``

Whitelist by Email Address
##########################

We send from:

* ``handshake@notifications.joinhandshake.com``
* ``handshake@mail.joinhandshake.com``
* ``handshake@m.joinhandshake.com``

It is possible to configure a custom reply-to email address, by default it is set to

* ``handshake@mail.joinhandshake.com``
* ``handshake@notifications.joinhandshake.com``
* ``handshake@m.joinhandshake.com``
