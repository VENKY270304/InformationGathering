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


## OUTPUT:
![267652126-3ec70a48-8834-4880-977b-601ef3a1863b](https://github.com/VENKY270304/InformationGathering/assets/124234106/9935ef6e-560d-485b-ad99-c21e2398a91b)
## Finding IP Address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## OUTPUT:
![267951536-1e04cba2-efea-4583-a15c-fd2f9289e36d](https://github.com/VENKY270304/InformationGathering/assets/124234106/f871987d-f5ee-4c3e-a83d-802526b3204b)
## Finding Hosting Company:
get further detail by using ip2location.com website.
## Output:
![267652938-f0e705e6-32d1-4317-b4a4-02d7c126759a](https://github.com/VENKY270304/InformationGathering/assets/124234106/7a3c205a-99cd-434d-8b4e-5029b7c26be5)

## Web Server Fingerprinting:
## Netcat:
```
nc 172.17.52.118 80
```
## OUTPUT:
![270240799-d1f0210b-9156-404f-8c02-76d510c1811b](https://github.com/VENKY270304/InformationGathering/assets/124234106/9896876c-8dfc-470c-b5f5-6c4beb563c4b)

## Nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
![270241043-fa84cef7-ca0c-4f88-abbb-74e2010e6997](https://github.com/VENKY270304/InformationGathering/assets/124234106/4feebb0e-9a12-4c4f-b25b-1f13d5b6ffe1)

## Output:
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
