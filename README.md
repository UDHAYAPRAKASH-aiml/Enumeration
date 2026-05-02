# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

# Pen Test Tools Categories

Following categories of penetration testing tools are identified:

## Information Gathering

# Google Hacking

Google hacking (Google dorking) uses advanced search operators to find specific or sensitive information indexed by search engines.

---

## site:
Searches within a specific domain.

![Site Operator](https://github.com/user-attachments/assets/0e1d33c0-7a87-4ead-b4b3-303c1e867c26)

### Description of the Output
- Displays all indexed pages within the specified domain (e.g., yahoo.com).  
- Helps identify subdomains and publicly available content.  
- Useful for mapping the structure of a website.  

---

## filetype:
Searches for specific file formats.

![Filetype Operator](https://github.com/user-attachments/assets/5c1026cf-9b6a-423c-9935-0b38ae9afee0)

### Description of the Output
- Lists files of a particular type (e.g., PDF) within a domain.  
- Helps locate downloadable documents.  
- Useful for identifying exposed reports or sensitive files.  

---

## intext:
Searches for specific text inside webpage content.

![Intext Operator](https://github.com/user-attachments/assets/2a3f06c0-1625-486e-a63e-93bf7601fcf2)

### Description of the Output
- Displays pages containing the specified keyword in the body.  
- Helps identify sensitive data like passwords or configurations.  
- Useful for content-based information gathering.  

---

## inurl:
Searches for keywords in URLs.

![Inurl Operator](https://github.com/user-attachments/assets/93c34e18-f871-4413-92fd-7a50bd67de02)

### Description of the Output
- Lists URLs containing specific keywords (e.g., admin).  
- Helps identify login pages or admin panels.  
- Useful for discovering hidden endpoints.  

---

## intitle:
Searches for keywords in page titles.

### Description of the Output
- Displays pages with matching keywords in the title.  
- Helps identify directory listings or indexed pages.  
- Useful for finding exposed directories.  

---

## link:
Searches for pages linking to a specific domain.

![Link Operator](https://github.com/user-attachments/assets/440a074e-76c8-44bd-aba0-27de6f43ade7)

### Description of the Output
- Shows backlinks to the target website.  
- Helps understand site references and relationships.  
- Useful for reconnaissance and SEO insights.  

---

## cache:
Displays cached versions of webpages.

![Cache Operator](https://github.com/user-attachments/assets/2963d70f-51fb-4237-a072-aebaa615f5c1)

### Description of the Output
- Shows stored (cached) version of a webpage by Google.  
- Useful when the live site is down or content is removed.  
- Helps analyze previous versions of a page.  

---

## link (duplicate case):
![Link Operator 2](https://github.com/user-attachments/assets/ee290eec-b405-4dd6-a940-8838bef3f49d)

### Description of the Output
- Displays pages linking to the target domain.  
- Helps in identifying external references.  

---

# DNS Enumeration

## DNS Recon

![DNS Recon Output](https://github.com/user-attachments/assets/c09ab4ea-8993-4bc6-9d3a-02f37329d851)

### Description of the Output
- Lists DNS records such as A, MX, NS, TXT, SPF.  
- Identifies name servers and mail servers.  
- Shows possible zone transfer results.  
- Helps map domain infrastructure.  

---

## dnsenum

![dnsenum Output 1](https://github.com/user-attachments/assets/e3c4fe1b-e153-4d28-8c6e-66dce2369a8c)  
![dnsenum Output 2](https://github.com/user-attachments/assets/e929bf14-7373-4b38-8beb-d497ba949cd9)

### Description of the Output
- Displays domain IP addresses and subdomains.  
- Lists MX records and name servers.  
- Shows brute-forced subdomains.  
- Provides network range and WHOIS details.  
- Helps in deep DNS enumeration.  

---

## smtp-user-enum

![SMTP User Enum](https://github.com/user-attachments/assets/97b3edae-1cae-4843-aaa1-7a8b67876cb3)

### Description of the Output
- Lists valid usernames on the SMTP server.  
- Uses commands like VRFY, EXPN, RCPT TO.  
- Helps identify existing user accounts.  
- Useful for authentication testing.  

---

## Telnet for SMTP Enumeration

![Telnet Output](https://github.com/user-attachments/assets/11958490-af0c-4a2d-b567-abbd6d5b5e05)

### Description of the Output
- Shows connection to SMTP server on port 25.  
- Displays server banner information.  
- Allows manual execution of SMTP commands.  
- Helps verify user existence and server behavior.  

---

## nmap –script smtp-enum-users.nse

![Nmap SMTP Enum](https://github.com/user-attachments/assets/a2b10581-7b1a-4daf-9dd1-4119ca2caa30)

### Description of the Output
- Enumerates valid SMTP users automatically.  
- Uses VRFY, EXPN, and RCPT commands.  
- Displays discovered usernames.  
- Useful for automated user enumeration.  

---
## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

