# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

### Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:
Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![1](https://github.com/Aakash0407/InformationGathering/assets/118799103/6a9f4cae-171f-4a15-9f16-2183db885f28)

### Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![2](https://github.com/Aakash0407/InformationGathering/assets/118799103/daaa3ee1-e043-4971-a854-af26c61b5f83)

### Finding Hosting Company
get further detail by using ip2location.com website.

## Output:
![3](https://github.com/Aakash0407/InformationGathering/assets/118799103/b0914500-f468-4a40-835a-7bd1417352b0)

## History of the website:
## Output:
https://web.archive.org/
![4](https://github.com/Aakash0407/InformationGathering/assets/118799103/60b168b7-3495-40a5-bdfe-d2d6472fbdd5)
```
nc 172.17.52.118 80
```
![5](https://github.com/Aakash0407/InformationGathering/assets/118799103/9753fbf4-69e2-47f5-b5e2-7e4cf8c13e67)

### nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![6](https://github.com/Aakash0407/InformationGathering/assets/118799103/04cf9242-82ca-4616-8c5e-dd40b65d5d1b)

### Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![7](https://github.com/Aakash0407/InformationGathering/assets/118799103/6c420ae5-7991-4696-9f19-a628fb09a6e1)
![8](https://github.com/Aakash0407/InformationGathering/assets/118799103/9a657cbd-42b5-43f9-bdc1-238e27e2afc5)

### httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![9](https://github.com/Aakash0407/InformationGathering/assets/118799103/55253bc3-6c40-48d5-8a71-b3a47094b564)

## Tracing the Location
### TCP Traceroute:
````
sudo traceroute -T www.saveetha.ac.in
````
## Output:
![10](https://github.com/Aakash0407/InformationGathering/assets/118799103/6eb0602e-82a2-47e7-b179-a6e21c3f2fe5)

### UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![11](https://github.com/Aakash0407/InformationGathering/assets/118799103/e74c96f6-45fc-4b9a-b2a1-6954751f9bbe)

### ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![12](https://github.com/Aakash0407/InformationGathering/assets/118799103/9a03b174-8b34-464d-ab54-57a6d7a6e48c)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
