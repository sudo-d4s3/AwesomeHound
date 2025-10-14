# AwesomeHound [![AwesomeHound](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome tools related to Bloodhound.

There is no pre-established order of items in each category. If you want to contribute, please create an issue.

## BloodHound Backends

 - [Legacy BloodHound](https://github.com/SpecterOps/BloodHound-Legacy) - Original Six Degrees of Domain Admin 
 - [BloodHound Community Edition](https://github.com/SpecterOps/BloodHound) - Six Degrees of Domain Admin 
 - [PlumHound](https://github.com/PlumHound/PlumHound) - Bloodhound Reporting for Blue and Purple Teams 
 
## Official Data Collectors

 - [SharpHound](https://github.com/SpecterOps/SharpHound) - C# Data Collector for BloodHound 
 - [AzureHound](https://github.com/SpecterOps/AzureHound) - Azure Data Exporter for BloodHound
 - [JamfHound](https://github.com/SpecterOps/JamfHound) - Python3 project designed to collect and identify attack paths in Jamf Pro tenants
 - [1PassHound](https://github.com/SpecterOps/1PassHound) - 1Password for Business OpenGraph extension
 - [GitHound](https://github.com/SpecterOps/GitHound) - BloodHound OpenGraph collector for GitHub
 - [SnowHound](https://github.com/SpecterOps/SnowHound) - BloodHound extension for Snowflake
 - [MSSQLHound](https://github.com/SpecterOps/MSSQLHound) - PowerShell collector for adding MSSQL attack paths to BloodHound

## Unofficial Data Collectors

 - [BloodHound.py Legacy](https://github.com/dirkjanm/BloodHound.py) - Python based ingestor for BloodHound Legacy, based on Impacket
 - [BloodHound.py CE](https://github.com/dirkjanm/BloodHound.py/tree/bloodhound-ce) - Python based ingestor for BloodHound CE, based on Impacket
 - [RustHound Legacy](https://github.com/NH-RED-TEAM/RustHound) - Active Directory data ingestor for BloodHound Legacy written in Rust
 - [RustHound CE](https://github.com/g0h4n/RustHound-CE) - Active Directory data ingestor for BloodHound Community Edition written in Rust
 - [BOFHound](https://github.com/fortalice/bofhound) - Generate BloodHound compatible JSON from logs written by ldapsearch BOF, pyldapsearch and Brute Ratel's LDAP Sentinel
 - [SOAPHound](https://github.com/FalconForceTeam/SOAPHound) - .NET data collector for Active Directory using Active Directory Web Services instead of LDAP.
 - [SoapHound.py](https://github.com/j4s0nmo0n/Soaphound.py) - Bloodhound python Ingestor using ADWS 
 - [vCenterHound](https://github.com/MorDavid/vCenterHound) - Collect infrastructure and permissions data from vCenter and export it as a BloodHound‑compatible graph

 ## Data Converters

 - [ADExplorerSnapshot.py](https://github.com/c3c/ADExplorerSnapshot.py) - ADExplorerSnapshot.py is an AD Explorer snapshot parser. It is made as an ingestor for BloodHound, and also supports full-object dumping to NDJSON
 - [DCSyncHound](https://github.com/MorDavid/DCSyncHound) - This script analyzes the DCSync output file from several tools (Mimikatz, Secretsdump, etc) and combine them into a single xlsx file and load the details into bloodhound


## Tools that do things with BloodHound Data

 - [Rakound-NG](https://github.com/Tamhackti/Rakound-NG) - tool written in Python that interacts with BloodHound database (neo4j) to retrieve data, add NTLM hashes and cracked passwords
 - [LudusHound](https://github.com/bagelByt3s/LudusHound) - transforms BloodHound data into a fully functional, Active Directory replica environment via Ludus for controlled testing
 - [F4keH0und](https://github.com/DEF-CON-Group-420/F4keH0und) - Deception implementation through analysis of BloodHound data 
