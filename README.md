# Whitelist for UniFi Ad Blocking

Domains allowed for Ad blocking

While the UniFi Ad Blocking is a basic system, it can sometimes block to many things and will break some sites or services by default. With this list we try to add whitelisted domains that can be added to the UniFi system, to make sure things keep working.

This list includes domains that are better to be whitelisted when using the UniFi Ad Blocking option. For example the Google ads via google search, which some people use to find deals online. But also things like NLZiet and others collected over the last couple of months.

To add this simply go to your UniFi Network Settings:

- Settings > Security > Traffic & Firewall Rules
- Create Entry

- Name: Whitelisted Domains
- Action: Allow
- Source: All Devices
- Destination: Domain Name
- Schedule: Always
- Then batch add the content of the allowlist.txt and click Save
