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
## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/59820041-8367-453e-a81a-a5bccabd606c)


## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```

## Output:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/9fd666d7-178e-44a3-a189-bbe16245b252)

## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/22fc1cdb-d010-489d-a09e-ef6af13fe456)

## History of the wbsite:

## Output:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/cc0a50aa-e7ab-498c-ad37-92b2c37f2f43)

## Web server Fingerprint:

## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/f15dc628-7530-46c0-b671-d350455ee9e4)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/be4848d6-95e1-45fc-ad89-e9cae00d56b4)

## Whatweb:
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
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/42dfba74-132f-42f6-8a70-435a3b22c2a4)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/76d3af04-1977-4993-a40a-030c97deff77)

## Tracing the Location:

## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/5daa88ef-bf8f-49ce-a3fd-35697b1c4e7a)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/a187efab-e6df-4a51-a743-b3662f88952d)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![image](https://github.com/SivaramakrishnanBaskar/InformationGathering/assets/119476322/ae5e5156-dec5-405d-b9f9-f3c43a080b2c)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
