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

<details>
<summary>Scanning Network Tools</summary>

* Scanning tool:
    - nmap(network mapping) :~
        - OS discovery
        - host discovery
        - port scanning
        - service version discovery
        - Netbios(using nse)
        - SMTP enumeration
        - nmap <option> <target_ip_address>
    - hping
        - ip spoofing
    - Metasploit
        - SMTP Enumeration
    - NetScanTool Pro

* Host Discovery :~
    - ARP Ping Scan = -sn -PR 
    - UDP Ping Scan = -sn -PU
    - ICMP Ping Scan 
        - ICMP ECHO Ping = -sn -PE
            - ICMP ECHO Ping Sweep = -sn -PE <full_subnet>
              - tools:
                - Angry IP Scanner
                 ```console
                     https://angryip.org 
                 ```
                - Advanced IP Scanner
                 ```console
                     https://www.advanced-ip-scanner.com
                 ```                        
    - ICMP Timestamp Ping = -sn -PP
    - ICMP Address Mask Ping = -sn -PM
    - TCP Ping Scan 
        - TCP SYN Ping = -sn -PS
        - TCP ACK Ping = -sn -PA
    - IP Protocol Scan = -sn -PO

* Unicornscan :~
    - OS Discovery tool 
    - command-line tool
* nmap script engine :~
   ```comsole
        nmap --script smb-os-discovery.nse <ip_or_subnet>
   ```
* IPv6/IPv4 Fingerprinting :~
    - ping6 <ipv6_address> or nmap -6 <ipv6_addresss>
    - ping4 <ip_address> or nmap -4 <ipadress>           
* Proxy Switcher :~
  ```console 
       https://www.proxyswitcher.com
  ```     
* CyberGhost VPN Source :~
  ```console
        https://www.cyberghostvpn.com
  ```  
</details>

<details>
<summary>enumeration tools</summary>

* nbtstat (use in windows):~
   - display NetBIOS name tables, cache, and NetBIOS sessions
* SnmpWalk :~
   - SNMP enumaration
* Active Directory Explorer (AD Explorer) :~
   - LDAP Enumeration
* superenum :~
   - provides detailed enumeration data such as users, shares, domains, and services of the target
* RPCScan :~    
   - NFS enumeration
* dig(Domain Information Groper) :~
   - query DNS servers to obtain DNS record information
   - using DNS zone transfer
* nmap -p 25 --script=smtp-enum-users [Target IP Address] :~
   - using this to enum SMTP 
   - --script=argument , smtp-enum-users=script
* Global Network Inventory :~
   - for enumerate information about target system
* enumerating user accounts :~
   - PsTools :~
      - PsExec 
      - PsFile
      - PsGetSid
      - PsKill
      - PsInfo
      - PsList
      - PsLoggedOn
      - PsLogList
      - PsPasswd
      - PsShutdown
* Net view :~
   - command-line utility and ist of all the shared resources of a remote host or workgroup

<details>
<summary>Vulnerability Analysis</summary>

* Tools :~
  - Nessus
  - GFI Lan Guard
  - openvas
  - Nikto
  - Qualys
  - skipfish
  
* AI-Powered Vulnerability Assessment Tool :~
  - Equixly
  - SmartScanner 
  - CodeDefender 
  - Corgea 
  - Fluxguard 
  - DryRun Security 
  - Pentest Copilot  

* websites for stored previous vuln :~
  - Common Vulnerability Scorimg System(CVSS)
  - Common Vulnerability and Explosures(CVE)
  - National Vulnerability Database(NVD)
  - Common Weakness Enumaration(CWE)



</details>         