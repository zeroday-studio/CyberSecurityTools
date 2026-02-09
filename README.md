# CyberSecurityTools
<details>
<summary>reconnaissance and footprinting tools</summary>

* google hacking database(GHDB)(google dorks) :~
    ```console
         https://www.exploit-db.com/google-hacking-database
    ```
* SearchSploit :~
    - this is a command-line tool, same as the GHDB and you can use it in offline    
* sgpt :~
    - bash sgpt.sh
* shodan :~
    - Shodan is a search engine. It is used to detect devices and networks with vulnerabilities
    //or
    - to determin os
    ```console
         https://www.shodan.io/
    ```
* advance image serach :~
    ```console
         https://www.google.com/advanced_image_search
    ``` 
* image search tool:
    - tineye reverse image search
    ```console
         https://tineye.com/
    ```             
* advance search :~
    ```console
         https://www.google.com/advanced_search
    ```
* reverse image search in Google :~
    ```console
         https://www.google.com/imghp
    ```
* video analysis tools :~
    ```console
         https://ytlarge.com/data-viewer
    ```
* Netcraft :~
    - to find subdomain
    //or
    - to determin os
        ```console
             https://www.netcraft.com 
        ```                                  
* DNSdumpster :~
    - find subdomain
    //or
    - for DNS or quaryies
    ```console
         https://dnsdumpster.com
    ```
* Pentest-Tools Find Subdomains 
    ```console
         https://pentest-tools.com
     ```     
 * command for find TLDs and subdomains :~
    - "dig" = to query the authoritative name servers (NS records) 
    - "sublist3r" = to serach subdomains
* Archive :~
    - Extracting Website Information
        ```console
             https://archive.org 
        ```
    - photon
        - command-line tool to retrieve the archive.org links of the target website
        - command :~
            - python photon.py         
* Spokeo (people search services)
    ```console
         https://www.spokeo.com/
    ```
* censys :~
    - find the IOT devices
    - to determin os
    ```console
         https://censys.io
    ```             
* Recon-ng :~
    - powerfull tool for Reconnaissance for information gathering
* whois domain tool :~
    - WHOIS helps identify who owns a domain and how it is registered
    ```console
         https://whois.domaintools.com
    ```
* nslookup :~
  - for DNS or quaryies and ip address info
  - commands
   ```console 
     - nslookup
     - set type=a (a=A record)
     - www.certifiedhacker.com(domain name)
     - set type=cname
     - certifiedhacker.com(non-authoritative name)
     - set type=a(if we wnt the primary email ip address u can use it again)
     - enter primary email address
   - for example DNS records:
     - mx = for mail
     - ns = for servers
     - a = for ipv4
     - aaaa = for ipv6
   ```  
  //or use
* Kloth(same as nslookup)             
    ```console
         https://www.kloth.net/services/nslookup.php
    ```     
* Perform Network Footprinting :~
    - tracert (for-windows)
      - command:
       ```console
         - tracert <website_or_domain_name>
         - tracert /?
         - tracert -h <min_no_hop> <website_or_domain_name>
       ```
    - tracroute (for-linux)  
      - command:
       ```console
         - traceroute <website_or_domain_name> 
       ```
    //or 
    - NetScanTool Pro :~
       ```console
            https://www.netscantools.com
       ``` 
    //or
    - Pingplotter :~
       ```console
            https://www.pingplotter.com
       ```              
* eMailTrackerPro (email tracking tool) 
  //or 
* MXtoolbox(reverse dns lookup)or Social Catfish or ip2location
* theHarvester
    - use this tool to perform enumeration on the LinkedIn and its command line tool
    ```console
        theHarvester -d microsoft -l 200 -b linkedin 
    ```
    - Gathering email addresses
    ```console
        theharvester -d microsoft.com -l 200 -b baidu
    ```
* Buzzsumo(get information on social media) 
    ```console
         https://buzzsumo.com 
    ```                          
* DNSRecon(reverse dns lookup) :~
    ```console
         dnsrecon -r <ip_range>
    ```  
* automated footprinting task advance tool :~ 
    - Maltego(used for link analysis and footprinting)
     ```console
          https://www.maltego.com 
     ``` 
    - FOCA(to find metadata)  
     ```console
          https://www.elevenpaths.com
     ```
    - subfinder
        - command-line too and subdomain discovery tool
    - OSINT Framework :~
     ```console
          https://osintframework.com/
     ```
    - Recon-Dog
        - all-in-one tool for all basic information gathering and command line tool 
    - Billcipher
        - supports Python 2, Python 3, and Ruby                                
</details>
