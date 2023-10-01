# External Penetration Testing By TCM-Security { note }
this repo contains my study notes and free course link for the External Penetration testing course by TCM Security

```
this course is not a hands on course .this is a methodology course. ENJOY
```

## Objectives
- trying to attack from the outside.
- in a external ,no need to test web app testing.

[Pasted image 20230929120524](https://github.com/krishanthan4/External_Penetration_Testing_By_TCM-Security/assets/122454062/ad904793-4cb1-48ed-bfad-9f1d5e7de0b3)

[Pasted image 20230929120551](https://github.com/krishanthan4/External_Penetration_Testing_By_TCM-Security/assets/122454062/8e881aed-d87e-40ec-873e-8625a911d5c7)

## Rules of Engagement Doc
- this is a high level overview of a test scopes and details.
- this is a must do agreement.
## Out of Scope
- Denial of Service (DoS)
- Social Engineering
## verify the scope
- www.bgp.he.net
## client Communication 
- send a email that we are going to begin the pentest.
## Attack Strategy
- Think of External pentest like <span style="color:#ffff00">home Security</span>.
- Low chances of <span style="color:#d95e5e">RCE</span>,high chance of weak passwords.
- OSINT.
- Logical Guessing.
## Vulnerability Scanner
- openVAS / Nessus  / 
get the vulnerability scanning report to a Excel sheet by something.

## hunting breached passwords
- breach-parse   > tool written by heathadams.
- www.dehashed.com
## Identifying Employees & Emails
- Phonebook.cz
## Bypassing MFA
- mfasweep tool

## Report Writing 
- don't put passwords in report
## Weak Password Policy
- OSINT for Password policies of the organisation because sometimes it would be public.
## Insufficient Patching
## Default Credentials
## Insufficient Encryption

![Pasted image 20230929164838](https://github.com/krishanthan4/External_Penetration_Testing_By_TCM-Security/assets/122454062/3fe70391-968c-44ad-8e8c-48e0b9882b91)



## Information Disclosure
  ![Pasted image 20231001233317](https://github.com/krishanthan4/External_Penetration_Testing_By_TCM-Security/assets/122454062/8d0eba1d-337f-4edd-bdff-de5ac945fa45)

## Username Enumeration
## Default Web Pages
## Open Mail Repays
## Unexpected Perimeter Services
- telnet ,RDP
## Insufficient Traffic Blocking
- this one want to talk with your client
- because if the client's customers are not coming from US,then block the US traffic otherwise ,bots can search for vulnerabilities and exploit it.
## Undetected Malicious Activity (informational)
- if attacker run brute forcing, or port scanning, the victim need to get noticed .otherwise this will be a vulnerability
## Historical Account Compromises (informational)
- this is a list of we found from OSINT or Dark web ,the credentials for some thing related to the company.
## Client Debriefs
- do a PPT or pdf version of a High level of our External Pentest.

## Attestation Letter
- this is a quick and short letter that will hand over to the client ,obviously we have to write :)
## Retesting
- we have to retest the pentest after client patched the vulnerabilities
