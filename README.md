# netpractice
*This project has been created as a part of the 42 curriculum by sabruma*

## Description
This is a project that aims to practice simple network configurations. The interface is provided by 42, each student is then required to configure 10 different network topologies with correct static TCP/IP addressing. The goals for each level are listed at the top of the page, and must all be completed before doing the next level.

## Instructions
### How to run
- First, download the file attached to the project’s page.
- Then, extract the files into any folder of your choice.
- In this folder, open index.html in your web browser, or run the provided run.sh if available. 
- This shell script will launch a web server and open your preferred web browser to the dedicated page.
- The interface should open in your web browser

Don't forget to enter your login before starting!

### Submission requirements
To submit for evaluation you should do all 10 levels. But beware! For each completed level you should export your configuration once you met all the requirements at the top of the level page, resulting in a grand total of 10 JSON files (one per level). These files should be placed at the repository root, alongside with a README.md file like this one.

To export your configuration, just click the "Get my config" button at the top of the level page before moving on to the next. This will trigger a download of the .json file of your current configuration, prompting you to choose a location to save it to. The exported files must be named exactly levelX.json, where X is the level number (i.e. level1.json etc..).

Don't forget to click the "Ckeck again" button before exporting!

## Resources
Networking concepts studied and applied:
- IPv4 addressing, subnet masks, CIDR notation
- Network address, broadcast address, usable host range
- Default gateway, static routing, routing tables
- Switch vs. router (L2 forwarding vs. L3 routing)
- Private IP ranges (RFC 1918) and public IP addressing
- VLSM (Variable Length Subnet Masking): using different netmasks within the same topology
- Route summarization / aggregation: combining multiple routes into a single entry
- ARP, ICMP, and basic packet forwarding logic
- OSI layers 1–3 and TCP/IP model