## Exchange Hosteur Security Report
Dernier rapport de securité de la plateforme Exchange Hosteur

## Frontend Services
![logo](img/logo-hosteur_2021.png)

### Exchange Information
	Name: Frontend FRD-AX223511
	Generation Time: 09/15/2022 08:12:22
	Version: Exchange 2019 CU12
	Build Number: 15.02.1118.012
	Exchange IU or Security Hotfix Detected: 
		Security Update for Exchange Server 2019 Cumulative Update 12 (KB5014261)
		Security Update for Exchange Server 2019 Cumulative Update 12 (KB5015322)

#### Security Vulnerability
	IIS module anomalies detected: False
	Security Vulnerability: Download Domains are not configured. You should configure them to be protected against CVE-2021-1730.
		Configuration instructions: https://aka.ms/HC-DownloadDomains
	Security Vulnerability: CVE-2022-24516, CVE-2022-21979, CVE-2022-21980, CVE-2022-24477, CVE-2022-30134
		Extended Protection should be configured. Current config:

        VirtualDirectory                   Value  SupportedValue  ConfigSupported  RequireSSL      ClientCertificate  
        Default Web Site/API               None   Require         False            False           Ignore             
        Exchange Back End/API              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/Autodiscover      None   None            True             False           Ignore             
        Exchange Back End/Autodiscover     None   None            True             True (128-bit)  Ignore             
        Default Web Site/ECP               None   Require         False            False           Ignore             
        Exchange Back End/ECP              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/EWS               None   Allow           False            False           Ignore             
        Exchange Back End/EWS              None   Require         False            True (128-bit)  Ignore             
        Default Web                        None   Allow           False            False           Ignore             
        Site/Microsoft-Server-ActiveSync                                                                              
        Exchange Back                      None   Require         False            True (128-bit)  Ignore             
        End/Microsoft-Server-ActiveSync                                                                               
        Default Web Site/OAB               None   Require         False            False           Ignore             
        Exchange Back End/OAB              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/Powershell        None   Require         False            False           Accept             
        Exchange Back End/Powershell       None   Require         False            True (128-bit)  Accept             
        Default Web Site/OWA               None   Require         False            False           Ignore             
        Exchange Back End/OWA              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/RPC               None   Require         False            False           Ignore             
        Exchange Back End/RPC              None   Require         False            False           Ignore             
        Default Web Site/MAPI              None   Require         False            False           Ignore             
        Exchange Back                      None   Require         False            True (128-bit)  Ignore             
        End/PushNotifications                                                                                         
        Exchange Back End/RPCWithCert      None   Require         False            False           Ignore             
        Exchange Back End/MAPI/emsmdb      None   Require         False            True            Ignore             
        Exchange Back End/MAPI/nspi        None   Require         False            True            Ignore             


	For more information about Extended Protection and how to configure, please read this article: https://aka.ms/HC-ExchangeEPDoc

---
### Exchange Information
	Name: Frontend FRD-AX225331
	Generation Time: 09/15/2022 08:02:32
	Version: Exchange 2019 CU12
	Build Number: 15.02.1118.012
	Exchange IU or Security Hotfix Detected: 
		Security Update for Exchange Server 2019 Cumulative Update 12 (KB5014261)
		Security Update for Exchange Server 2019 Cumulative Update 12 (KB5015322)

#### Security Vulnerability
	IIS module anomalies detected: False
	Security Vulnerability: Download Domains are not configured. You should configure them to be protected against CVE-2021-1730.
		Configuration instructions: https://aka.ms/HC-DownloadDomains
	Security Vulnerability: CVE-2022-24516, CVE-2022-21979, CVE-2022-21980, CVE-2022-24477, CVE-2022-30134
		Extended Protection should be configured. Current config:

        VirtualDirectory                   Value  SupportedValue  ConfigSupported  RequireSSL      ClientCertificate  
        Default Web Site/API               None   Require         False            False           Ignore             
        Exchange Back End/API              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/Autodiscover      None   None            True             False           Ignore             
        Exchange Back End/Autodiscover     None   None            True             True (128-bit)  Ignore             
        Default Web Site/ECP               None   Require         False            False           Ignore             
        Exchange Back End/ECP              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/EWS               None   Allow           False            False           Ignore             
        Exchange Back End/EWS              None   Require         False            True (128-bit)  Ignore             
        Default Web                        None   Allow           False            False           Ignore             
        Site/Microsoft-Server-ActiveSync                                                                              
        Exchange Back                      None   Require         False            True (128-bit)  Ignore             
        End/Microsoft-Server-ActiveSync                                                                               
        Default Web Site/OAB               None   Require         False            False           Ignore             
        Exchange Back End/OAB              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/Powershell        None   Require         False            False           Ignore             
        Exchange Back End/Powershell       None   Require         False            True (128-bit)  Accept             
        Default Web Site/OWA               None   Require         False            False           Ignore             
        Exchange Back End/OWA              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/RPC               None   Require         False            False           Ignore             
        Exchange Back End/RPC              None   Require         False            False           Ignore             
        Default Web Site/MAPI              None   Require         False            False           Ignore             
        Exchange Back                      None   Require         False            True (128-bit)  Ignore             
        End/PushNotifications                                                                                         
        Exchange Back End/RPCWithCert      None   Require         False            False           Ignore             
        Exchange Back End/MAPI/emsmdb      None   Require         False            True            Ignore             
        Exchange Back End/MAPI/nspi        None   Require         False            True            Ignore             


	For more information about Extended Protection and how to configure, please read this article: https://aka.ms/HC-ExchangeEPDoc

---
### Exchange Information
	Name: Frontend FRD-AX223512
	Generation Time: 09/15/2022 08:19:58
	Version: Exchange 2019 CU12
	Build Number: 15.02.1118.012
	Exchange IU or Security Hotfix Detected: 
		Security Update for Exchange Server 2019 Cumulative Update 12 (KB5014261)
		Security Update for Exchange Server 2019 Cumulative Update 12 (KB5015322)

#### Security Vulnerability
	IIS module anomalies detected: False
	Security Vulnerability: Download Domains are not configured. You should configure them to be protected against CVE-2021-1730.
		Configuration instructions: https://aka.ms/HC-DownloadDomains
	Security Vulnerability: CVE-2022-24516, CVE-2022-21979, CVE-2022-21980, CVE-2022-24477, CVE-2022-30134
		Extended Protection should be configured. Current config:

        VirtualDirectory                   Value  SupportedValue  ConfigSupported  RequireSSL      ClientCertificate  
        Default Web Site/API               None   Require         False            False           Ignore             
        Exchange Back End/API              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/Autodiscover      None   None            True             False           Ignore             
        Exchange Back End/Autodiscover     None   None            True             True (128-bit)  Ignore             
        Default Web Site/ECP               None   Require         False            False           Ignore             
        Exchange Back End/ECP              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/EWS               None   Allow           False            False           Ignore             
        Exchange Back End/EWS              None   Require         False            True (128-bit)  Ignore             
        Default Web                        None   Allow           False            False           Ignore             
        Site/Microsoft-Server-ActiveSync                                                                              
        Exchange Back                      None   Require         False            True (128-bit)  Ignore             
        End/Microsoft-Server-ActiveSync                                                                               
        Default Web Site/OAB               None   Require         False            False           Ignore             
        Exchange Back End/OAB              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/Powershell        None   Require         False            False           Accept             
        Exchange Back End/Powershell       None   Require         False            True (128-bit)  Accept             
        Default Web Site/OWA               None   Require         False            False           Ignore             
        Exchange Back End/OWA              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/RPC               None   Require         False            False           Ignore             
        Exchange Back End/RPC              None   Require         False            False           Ignore             
        Default Web Site/MAPI              None   Require         False            False           Ignore             
        Exchange Back                      None   Require         False            True (128-bit)  Ignore             
        End/PushNotifications                                                                                         
        Exchange Back End/RPCWithCert      None   Require         False            False           Ignore             
        Exchange Back End/MAPI/emsmdb      None   Require         False            True            Ignore             
        Exchange Back End/MAPI/nspi        None   Require         False            True            Ignore             


	For more information about Extended Protection and how to configure, please read this article: https://aka.ms/HC-ExchangeEPDoc

---
### Exchange Information
	Name: Frontend FRD-AX225332
	Generation Time: 09/15/2022 08:04:45
	Version: Exchange 2019 CU12
	Build Number: 15.02.1118.012
	Exchange IU or Security Hotfix Detected: 
		Security Update for Exchange Server 2019 Cumulative Update 12 (KB5014261)
		Security Update for Exchange Server 2019 Cumulative Update 12 (KB5015322)

#### Security Vulnerability
	IIS module anomalies detected: False
	Security Vulnerability: Download Domains are not configured. You should configure them to be protected against CVE-2021-1730.
		Configuration instructions: https://aka.ms/HC-DownloadDomains
	Security Vulnerability: CVE-2022-24516, CVE-2022-21979, CVE-2022-21980, CVE-2022-24477, CVE-2022-30134
		Extended Protection should be configured. Current config:

        VirtualDirectory                   Value  SupportedValue  ConfigSupported  RequireSSL      ClientCertificate  
        Default Web Site/API               None   Require         False            False           Ignore             
        Exchange Back End/API              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/Autodiscover      None   None            True             False           Ignore             
        Exchange Back End/Autodiscover     None   None            True             True (128-bit)  Ignore             
        Default Web Site/ECP               None   Require         False            False           Ignore             
        Exchange Back End/ECP              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/EWS               None   Allow           False            False           Ignore             
        Exchange Back End/EWS              None   Require         False            True (128-bit)  Ignore             
        Default Web                        None   Allow           False            False           Ignore             
        Site/Microsoft-Server-ActiveSync                                                                              
        Exchange Back                      None   Require         False            True (128-bit)  Ignore             
        End/Microsoft-Server-ActiveSync                                                                               
        Default Web Site/OAB               None   Require         False            False           Ignore             
        Exchange Back End/OAB              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/Powershell        None   Require         False            False           Accept             
        Exchange Back End/Powershell       None   Require         False            True (128-bit)  Accept             
        Default Web Site/OWA               None   Require         False            False           Ignore             
        Exchange Back End/OWA              None   Require         False            True (128-bit)  Ignore             
        Default Web Site/RPC               None   Require         False            False           Ignore             
        Exchange Back End/RPC              None   Require         False            False           Ignore             
        Default Web Site/MAPI              None   Require         False            False           Ignore             
        Exchange Back                      None   Require         False            True (128-bit)  Ignore             
        End/PushNotifications                                                                                         
        Exchange Back End/RPCWithCert      None   Require         False            False           Ignore             
        Exchange Back End/MAPI/emsmdb      None   Require         False            True            Ignore             
        Exchange Back End/MAPI/nspi        None   Require         False            True            Ignore             


	For more information about Extended Protection and how to configure, please read this article: https://aka.ms/HC-ExchangeEPDoc

---
