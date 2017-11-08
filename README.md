# README

### Features
- Dynamic hosts supported.
- Easy to configure.


### How to use
1. Run the script to generate the config file.
2. Edit the config file to your liking.
3. Run the script again to get the newly generated file.

You can also look which functions the program provides by adding the '-h' commandline-option.


### The Configfile Options
- include_header: Adds copyright and other information.
- include_local_entries: Adds the localhost entries to the hosts file.
- include_hostname_in_local_entry: Adds the hostname of the machine to the hosts file.
- include_broadcasthost: Adds the 'broadcasthost' entry with 255.255.255.255
- addresses: The actual addresses to add
  - All entries should have the format: "address": [ "host1", "host2" ]
  - Address can either be an IP address or a dynamic host in the form of "dynamic:\<the host to lookup\>"