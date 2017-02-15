**Netmiko** 
 Contains tests of the Netmiko Library.

- **netmiko_multiprocess_backup_all_v0.1.py** - "copy run tftp" on multiple devices
- **netmiko_multiprocess_status_all_v0.1.py** - "show ___" on multiple devices

**Python** 
 Contains Python tests, Regex extractions of MAC, IP addresses...Etc.

- **unit_test_sh_ip_arp.py** - Take a "show ip arp" and transform in a table
- **unit_test_sh_mac.py** - Take a "show mac address-table" and transform in a table
- **concatenate_2_tables.py** - Take two previous tables and concatenate in readable format
- **mac_converter.py** - Convert mac address in EUI, Cisco, Microsoft format.

**textFSM** 
 Contains tests of the textFSM Python module

- **Templates** - Network2code templates for textFSM
- **unit_test_sh_interfaces_to_csv.py - convert "show interfaces" into an exploitable .csv
- **unit_test_sh_interfaces_to_table.py - convert "show interfaces" into an exploitable python list
  