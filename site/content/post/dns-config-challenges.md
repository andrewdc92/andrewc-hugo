+++
date = "2017-04-16T18:32:36-07:00"
draft = false
title = "Two Challenges to Personal DNS Configuration"

+++

Challenge #1: The connection between SOA records, NS(name server) records, and A (address) records.

From anecdotal experience, more people are familiar with the concept of an IP address and a domain name as individual concepts, but don’t understand how they’re related. Explaining the mapping between IP address numbers and name servers (what happens when you type in a URL and hit ‘search’) is important to establish before diving into the DNS record relationships. Once the concept of mapping is established, I can work with the user to run terminal commands to display and configure their A  & CNAME records. If we share understanding of the aforementioned records, understanding PTR records should be clear and we can discuss more customization options if they’re interested.

Challenge #2: Selecting the name server software

Determining the users' flavor of Linux/Unix before diving into software choices (Bind, powerDNS, djbdns, dnsmasq, etc). I would provide an existing resource (like a better-formatted version of this: https://en.wikipedia.org/wiki/Comparison_of_DNS_server_software) or create a custom document comparing/contrasting some of the popular DNS software choices.  For OSX users, if they’re not familiar, I’d recommend setting up Homebrew because it is an easy tool for installing software (can also be used to install DNS software like Bind, along with some of the popular static site generators like Hugo).

Configuring the name server to help recognize and prevent phishing/cache poisoning would also be a priority for certain clients, and I'd need to communicate the importance of properly setting up the various configurations in Bind, for example. The user should be comfortable pinging their DNS as a basic test for connectivity whenever they encounter an issue.
