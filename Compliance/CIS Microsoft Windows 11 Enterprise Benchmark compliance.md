# CIS Microsoft Windows 11 Enterprise Benchmark

**Version**: 2.0.0

**Date**: 03-07-2023

**Source**: [CIS Benchmark PDFs](https://downloads.cisecurity.org/)

## Benchmark compliance

|   | CIS Benchmark Recommendation | Set Correctly | GPO |
| - | ---------------------------- | ------------- | --- |
| **1** | **Account Policies** | | |
| **1.1** | **Password Policy** | | |
| 1.1.1 | (L1) Ensure 'Enforce password history' is set to '24 or more password(s)' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 1.1.2 | (L1) Ensure 'Maximum password age' is set to '365 or fewer days, but not 0' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 1.1.3 | (L1) Ensure 'Minimum password age' is set to '1 or more day(s)' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 1.1.4 | (L1) Ensure 'Minimum password length' is set to '14 or more character(s)' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 1.1.5 | (L1) Ensure 'Password must meet complexity requirements' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 1.1.6 | (L1) Ensure 'Relax minimum password length limits' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 1.1.7 | (L1) Ensure 'Store passwords using reversible encryption' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| **1.2** | **Account Lockout Policy** | | |
| 1.2.1 | (L1) Ensure 'Account lockout duration' is set to '15 or more minute(s)' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 1.2.2 | (L1) Ensure 'Account lockout threshold' is set to '5 or fewer invalid logon attempt(s), but not 0' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 1.2.3 | (L1) Ensure 'Allow Administrator account lockout' is set to 'Enabled' (Manual) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 1.2.4 | (L1) Ensure 'Reset account lockout counter after' is set to '15 or more minute(s)' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| **2** | **Local Policies** | | |
| **2.1** | **Audit Policy** | | |
| **2.2** | **User Rights Assignment** | | |
| 2.2.1 | (L1) Ensure 'Access Credential Manager as a trusted caller' is set to 'No One' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.2 | (L1) Ensure 'Access this computer from the network' is set to 'Administrators, Remote Desktop Users' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.3 | (L1) Ensure 'Act as part of the operating system' is set to 'No One' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.4 | (L1) Ensure 'Adjust memory quotas for a process' is set to 'Administrators, LOCAL SERVICE, NETWORK SERVICE' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.5 | (L1) Ensure 'Allow log on locally' is set to 'Administrators, Users' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.6 | (L1) Ensure 'Allow log on through Remote Desktop Services' is set to 'Administrators, Remote Desktop Users' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.7 | (L1) Ensure 'Back up files and directories' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.8 | (L1) Ensure 'Change the system time' is set to 'Administrators, LOCAL SERVICE' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.9 | (L1) Ensure 'Change the time zone' is set to 'Administrators, LOCAL SERVICE, Users' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.10 | (L1) Ensure 'Create a pagefile' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.11 | (L1) Ensure 'Create a token object' is set to 'No One' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.12 | (L1) Ensure 'Create global objects' is set to 'Administrators, LOCAL SERVICE, NETWORK SERVICE, SERVICE' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.13 | (L1) Ensure 'Create permanent shared objects' is set to 'No One' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.14 | (L1) Configure 'Create symbolic links' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.15 | (L1) Ensure 'Debug programs' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.16 | (L1) Ensure 'Deny access to this computer from the network' to include 'Guests, Local account' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.17 | (L1) Ensure 'Deny log on as a batch job' to include 'Guests' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.18 | (L1) Ensure 'Deny log on as a service' to include 'Guests' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.19 | (L1) Ensure 'Deny log on locally' to include 'Guests' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.20 | (L1) Ensure 'Deny log on through Remote Desktop Services' to include 'Guests, Local account' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.21 | (L1) Ensure 'Enable computer and user accounts to be trusted for delegation' is set to 'No One' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.22 | (L1) Ensure 'Force shutdown from a remote system' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.23 | (L1) Ensure 'Generate security audits' is set to 'LOCAL SERVICE, NETWORK SERVICE' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.24 | (L1) Ensure 'Impersonate a client after authentication' is set to 'Administrators, LOCAL SERVICE, NETWORK SERVICE, SERVICE' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.25 | (L1) Ensure 'Increase scheduling priority' is set to 'Administrators, Window Manager\Window Manager Group' (Automated) | :white_large_square: | |
| 2.2.26 | (L1) Ensure 'Load and unload device drivers' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.27 | (L1) Ensure 'Lock pages in memory' is set to 'No One' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.28 | (L2) Ensure 'Log on as a batch job' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.29 | (L2) Configure 'Log on as a service' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.30 | (L1) Ensure 'Manage auditing and security log' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.31 | (L1) Ensure 'Modify an object label' is set to 'No One' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.32 | (L1) Ensure 'Modify firmware environment values' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.33 | (L1) Ensure 'Perform volume maintenance tasks' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.34 | (L1) Ensure 'Profile single process' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.35 | (L1) Ensure 'Profile system performance' is set to 'Administrators, NT SERVICE\WdiServiceHost' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.36 | (L1) Ensure 'Replace a process level token' is set to 'LOCAL SERVICE, NETWORK SERVICE' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.37 | (L1) Ensure 'Restore files and directories' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.38 | (L1) Ensure 'Shut down the system' is set to 'Administrators, Users' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.2.39 | (L1) Ensure 'Take ownership of files or other objects' is set to 'Administrators' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3** | **Security Options** | | |
| **2.3.1** | **Accounts** | | |
| 2.3.1.1 | (L1) Ensure 'Accounts: Block Microsoft accounts' is set to 'Users can't add or log on with Microsoft accounts' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 2.3.1.2 | (L1) Ensure 'Accounts: Guest account status' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.1.3 | (L1) Ensure 'Accounts: Limit local account use of blank passwords to console logon only' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.1.4 | (L1) Configure 'Accounts: Rename administrator account' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>), [Windows 11 - LAPS](<../GP Reports/Windows 11 - LAPS.htm>) |
| 2.3.1.5 | (L1) Configure 'Accounts: Rename guest account' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.2** | **Audit** | | |
| 2.3.2.1 | (L1) Ensure 'Audit: Force audit policy subcategory settings (Windows Vista or later) to override audit policy category settings' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.2.2 | (L1) Ensure 'Audit: Shut down system immediately if unable to log security audits' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.3** | **DCOM** | | |
| **2.3.4** | **Devices** | | |
| 2.3.4.1 | (L1) Ensure 'Devices: Allowed to format and eject removable media' is set to 'Administrators and Interactive Users' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.4.2 | (L2) Ensure 'Devices: Prevent users from installing printer drivers' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.5** | **Domain controller** | | |
| **2.3.6** | **Domain member** | | |
| 2.3.6.1 | (L1) Ensure 'Domain member: Digitally encrypt or sign secure channel data (always)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.6.2 | (L1) Ensure 'Domain member: Digitally encrypt secure channel data (when possible)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.6.3 | (L1) Ensure 'Domain member: Digitally sign secure channel data (when possible)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.6.4 | (L1) Ensure 'Domain member: Disable machine account password changes' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.6.5 | (L1) Ensure 'Domain member: Maximum machine account password age' is set to '30 or fewer days, but not 0' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>), [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.6.6 | (L1) Ensure 'Domain member: Require strong (Windows 2000 or later) session key' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.7** | **Interactive logon** | | |
| 2.3.7.1 | (L1) Ensure 'Interactive logon: Do not require CTRL+ALT+DEL' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.7.2 | (L1) Ensure 'Interactive logon: Don't display last signedin' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.7.3 | (BL) Ensure 'Interactive logon: Machine account lockout threshold' is set to '10 or fewer invalid logon attempts, but not 0' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 2.3.7.4 | (L1) Ensure 'Interactive logon: Machine inactivity limit' is set to '900 or fewer second(s), but not 0' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.7.5 | (L1) Configure 'Interactive logon: Message text for users attempting to log on' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.7.6 | (L1) Configure 'Interactive logon: Message title for users attempting to log on' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.7.7 | (L2) Ensure 'Interactive logon: Number of previous logons to cache (in case domain controller is not available)' is set to '4 or fewer logon(s)' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.7.8 | (L1) Ensure 'Interactive logon: Prompt user to change password before expiration' is set to 'between 5 and 14 days' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.7.9 | (L1) Ensure 'Interactive logon: Smart card removal behavior' is set to 'Lock Workstation' or higher (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.8** | **Microsoft network client** | | |
| 2.3.8.1 | (L1) Ensure 'Microsoft network client: Digitally sign communications (always)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.8.2 | (L1) Ensure 'Microsoft network client: Digitally sign communications (if server agrees)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.8.3 | (L1) Ensure 'Microsoft network client: Send unencrypted password to third-party SMB servers' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.9** | **Microsoft network server** | | |
| 2.3.9.1 | (L1) Ensure 'Microsoft network server: Amount of idle time required before suspending session' is set to '15 or fewer minute(s)' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.9.2 | (L1) Ensure 'Microsoft network server: Digitally sign communications (always)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.9.3 | (L1) Ensure 'Microsoft network server: Digitally sign communications (if client agrees)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.9.4 | (L1) Ensure 'Microsoft network server: Disconnect clients when logon hours expire' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.9.5 | (L1) Ensure 'Microsoft network server: Server SPN target name validation level' is set to 'Accept if provided by client' or higher (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.10** | **Network access** | | |
| 2.3.10.1 | (L1) Ensure 'Network access: Allow anonymous SID/Name translation' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.2 | (L1) Ensure 'Network access: Do not allow anonymous enumeration of SAM accounts' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.3 | (L1) Ensure 'Network access: Do not allow anonymous enumeration of SAM accounts and shares' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.4 | (L1) Ensure 'Network access: Do not allow storage of passwords and credentials for network authentication' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.5 | (L1) Ensure 'Network access: Let Everyone permissions apply to anonymous users' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.6 | (L1) Ensure 'Network access: Named Pipes that can be accessed anonymously' is set to 'None' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.7 | (L1) Ensure 'Network access: Remotely accessible registry paths' is configured (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.8 | (L1) Ensure 'Network access: Remotely accessible registry paths and sub-paths' is configured (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.9 | (L1) Ensure 'Network access: Restrict anonymous access to Named Pipes and Shares' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.10 | (L1) Ensure 'Network access: Restrict clients allowed to make remote calls to SAM' is set to 'Administrators: Remote Access: Allow' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.11 | (L1) Ensure 'Network access: Shares that can be accessed anonymously' is set to 'None' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.10.12 | (L1) Ensure 'Network access: Sharing and security model for local accounts' is set to 'Classic - local users authenticate as themselves' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.11** | **Network security** | | |
| 2.3.11.1 | (L1) Ensure 'Network security: Allow Local System to use computer identity for NTLM' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.11.2 | (L1) Ensure 'Network security: Allow LocalSystem NULL session fallback' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.11.3 | (L1) Ensure 'Network Security: Allow PKU2U authentication requests to this computer to use online identities' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.11.4 | (L1) Ensure 'Network security: Configure encryption types allowed for Kerberos' is set to 'AES128_HMAC_SHA1, AES256_HMAC_SHA1, Future encryption types' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>), [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.11.5 | (L1) Ensure 'Network security: Do not store LAN Manager hash value on next password change' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.11.6 | (L1) Ensure 'Network security: Force logoff when logon hours expire' is set to 'Enabled' (Manual) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.11.7 | (L1) Ensure 'Network security: LAN Manager authentication level' is set to 'Send NTLMv2 response only. Refuse LM & NTLM' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.11.8 | (L1) Ensure 'Network security: LDAP client signing requirements' is set to 'Negotiate signing' or higher (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.11.9 | (L1) Ensure 'Network security: Minimum session security for NTLM SSP based (including secure RPC) clients' is set to 'Require NTLMv2 session security, Require 128- bit encryption' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.11.10 | (L1) Ensure 'Network security: Minimum session security for NTLM SSP based (including secure RPC) servers' is set to 'Require NTLMv2 session security, Require 128- bit encryption' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.12** | **Recovery console** | | |
| **2.3.13** | **Shutdown** | | |
| **2.3.14** | **System cryptography** | | |
| 2.3.14.1 | (L2) Ensure 'System cryptography: Force strong key protection for user keys stored on the computer' is set to 'User is prompted when the key is first used' or higher (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.15** | **System objects** | | |
| 2.3.15.1 | (L1) Ensure 'System objects: Require case insensitivity for non-Windows subsystems' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.15.2 | (L1) Ensure 'System objects: Strengthen default permissions of internal system objects (e.g. Symbolic Links)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **2.3.16** | **System settings** | | |
| **2.3.17** | **User Account Control** | | |
| 2.3.17.1 | (L1) Ensure 'User Account Control: Admin Approval Mode for the Built-in Administrator account' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.17.2 | (L1) Ensure 'User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode' is set to 'Prompt for consent on the secure desktop' or higher (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.17.3 | (L1) Ensure 'User Account Control: Behavior of the elevation prompt for standard users' is set to 'Automatically deny elevation requests' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.17.4 | (L1) Ensure 'User Account Control: Detect application installations and prompt for elevation' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.17.5 | (L1) Ensure 'User Account Control: Only elevate UIAccess applications that are installed in secure locations' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.17.6 | (L1) Ensure 'User Account Control: Run all administrators in Admin Approval Mode' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.17.7 | (L1) Ensure 'User Account Control: Switch to the secure desktop when prompting for elevation' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 2.3.17.8 | (L1) Ensure 'User Account Control: Virtualize file and registry write failures to per-user locations' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **3** | **Event Log** | | |
| **4** | **Restricted Groups** | | |
| **5** | **System Services** | | |
| 5.1 | (L2) Ensure 'Bluetooth Audio Gateway Service (BTAGService)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.2 | (L2) Ensure 'Bluetooth Support Service (bthserv)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.3 | (L1) Ensure 'Computer Browser (Browser)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.4 | (L2) Ensure 'Downloaded Maps Manager (MapsBroker)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.5 | (L2) Ensure 'Geolocation Service (lfsvc)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.6 | (L1) Ensure 'IIS Admin Service (IISADMIN)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.7 | (L1) Ensure 'Infrared monitor service (irmon)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.8 | (L1) Ensure 'Internet Connection Sharing (ICS) (SharedAccess)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.9 | (L2) Ensure 'Link-Layer Topology Discovery Mapper (lltdsvc)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.10 | (L1) Ensure 'LxssManager (LxssManager)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.11 | (L1) Ensure 'Microsoft FTP Service (FTPSVC)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.12 | (L2) Ensure 'Microsoft iSCSI Initiator Service (MSiSCSI)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.13 | (L1) Ensure 'OpenSSH SSH Server (sshd)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.14 | (L2) Ensure 'Peer Name Resolution Protocol (PNRPsvc)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.15 | (L2) Ensure 'Peer Networking Grouping (p2psvc)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.16 | (L2) Ensure 'Peer Networking Identity Manager (p2pimsvc)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.17 | (L2) Ensure 'PNRP Machine Name Publication Service (PNRPAutoReg)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.18 | (L2) Ensure 'Print Spooler (Spooler)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.19 | (L2) Ensure 'Problem Reports and Solutions Control Panel Support (wercplsupport)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.20 | (L2) Ensure 'Remote Access Auto Connection Manager (RasAuto)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.21 | (L2) Ensure 'Remote Desktop Configuration (SessionEnv)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.22 | (L2) Ensure 'Remote Desktop Services (TermService)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.23 | (L2) Ensure 'Remote Desktop Services UserMode Port Redirector (UmRdpService)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.24 | (L1) Ensure 'Remote Procedure Call (RPC) Locator (RpcLocator)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.25 | (L2) Ensure 'Remote Registry (RemoteRegistry)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.26 | (L1) Ensure 'Routing and Remote Access (RemoteAccess)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.27 | (L2) Ensure 'Server (LanmanServer)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.28 | (L1) Ensure 'Simple TCP/IP Services (simptcp)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.29 | (L2) Ensure 'SNMP Service (SNMP)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.30 | (L1) Ensure 'Special Administration Console Helper (sacsvr)' is set to 'Disabled' or 'Not Installed' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.31 | (L1) Ensure 'SSDP Discovery (SSDPSRV)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.32 | (L1) Ensure 'UPnP Device Host (upnphost)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.33 | (L1) Ensure 'Web Management Service (WMSvc)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.34 | (L2) Ensure 'Windows Error Reporting Service (WerSvc)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.35 | (L2) Ensure 'Windows Event Collector (Wecsvc)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.36 | (L1) Ensure 'Windows Media Player Network Sharing Service (WMPNetworkSvc)' is set to 'Disabled' or 'Not Installed' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.37 | (L1) Ensure 'Windows Mobile Hotspot Service (icssvc)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.38 | (L2) Ensure 'Windows Push Notifications System Service (WpnService)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.39 | (L2) Ensure 'Windows PushToInstall Service (PushToInstall)' is set to 'Disabled' (Automated) | :white_large_square: | |
| 5.40 | (L2) Ensure 'Windows Remote Management (WSManagement) (WinRM)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Remote Management](<../GP Reports/Windows Remote Management.htm>) |
| 5.41 | (L1) Ensure 'World Wide Web Publishing Service (W3SVC)' is set to 'Disabled' or 'Not Installed' (Automated) | :white_large_square: | |
| 5.42 | (L1) Ensure 'Xbox Accessory Management Service (XboxGipSvc)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.43 | (L1) Ensure 'Xbox Live Auth Manager (XblAuthManager)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.44 | (L1) Ensure 'Xbox Live Game Save (XblGameSave)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 5.45 | (L1) Ensure 'Xbox Live Networking Service (XboxNetApiSvc)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **6** | **Registry** | | |
| **7** | **File System** | | |
| **8** | **Wired Network (IEEE 802.3) Policies** | | |
| **9** | **Windows Defender Firewall with Advanced Security (formerly Windows Firewall with Advanced Security)** | | |
| **9.1** | **Domain Profile** | | |
| 9.1.1 | (L1) Ensure 'Windows Firewall: Domain: Firewall state' is set to 'On (recommended)' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.1.2 | (L1) Ensure 'Windows Firewall: Domain: Inbound connections' is set to 'Block (default)' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.1.3 | (L1) Ensure 'Windows Firewall: Domain: Outbound connections' is set to 'Allow (default)' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.1.4 | (L1) Ensure 'Windows Firewall: Domain: Settings: Display a notification' is set to 'No' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.1.5 | (L1) Ensure 'Windows Firewall: Domain: Logging: Name' is set to '%SystemRoot%\System32\logfiles\firewall\domainfw.log ' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.1.6 | (L1) Ensure 'Windows Firewall: Domain: Logging: Size limit (KB)' is set to '16,384 KB or greater' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.1.7 | (L1) Ensure 'Windows Firewall: Domain: Logging: Log dropped packets' is set to 'Yes' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.1.8 | (L1) Ensure 'Windows Firewall: Domain: Logging: Log successful connections' is set to 'Yes' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| **9.2** | **Private Profile** | | |
| 9.2.1 | (L1) Ensure 'Windows Firewall: Private: Firewall state' is set to 'On (recommended)' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.2.2 | (L1) Ensure 'Windows Firewall: Private: Inbound connections' is set to 'Block (default)' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.2.3 | (L1) Ensure 'Windows Firewall: Private: Outbound connections' is set to 'Allow (default)' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.2.4 | (L1) Ensure 'Windows Firewall: Private: Settings: Display a notification' is set to 'No' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.2.5 | (L1) Ensure 'Windows Firewall: Private: Logging: Name' is set to '%SystemRoot%\System32\logfiles\firewall\privatefw.log' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.2.6 | (L1) Ensure 'Windows Firewall: Private: Logging: Size limit (KB)' is set to '16,384 KB or greater' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.2.7 | (L1) Ensure 'Windows Firewall: Private: Logging: Log dropped packets' is set to 'Yes' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.2.8 | (L1) Ensure 'Windows Firewall: Private: Logging: Log successful connections' is set to 'Yes' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| **9.3** | **Public Profile** | | |
| 9.3.1 | (L1) Ensure 'Windows Firewall: Public: Firewall state' is set to 'On (recommended)' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.3.2 | (L1) Ensure 'Windows Firewall: Public: Inbound connections' is set to 'Block (default)' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.3.3 | (L1) Ensure 'Windows Firewall: Public: Outbound connections' is set to 'Allow (default)' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.3.4 | (L1) Ensure 'Windows Firewall: Public: Settings: Display a notification' is set to 'No' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.3.5 | (L1) Ensure 'Windows Firewall: Public: Settings: Apply local firewall rules' is set to 'No' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.3.6 | (L1) Ensure 'Windows Firewall: Public: Settings: Apply local connection security rules' is set to 'No' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.3.7 | (L1) Ensure 'Windows Firewall: Public: Logging: Name' is set to '%SystemRoot%\System32\logfiles\firewall\publicfw.log' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.3.8 | (L1) Ensure 'Windows Firewall: Public: Logging: Size limit (KB)' is set to '16,384 KB or greater' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.3.9 | (L1) Ensure 'Windows Firewall: Public: Logging: Log dropped packets' is set to 'Yes' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| 9.3.10 | (L1) Ensure 'Windows Firewall: Public: Logging: Log successful connections' is set to 'Yes' (Automated) | :ballot_box_with_check: | [Windows Defender Firewall](<../GP Reports/Windows Defender Firewall.htm>) |
| **10** | **Network List Manager Policies** | | |
| **11** | **Wireless Network (IEEE 802.11) Policies** | | |
| **12** | **Public Key Policies** | | |
| **13** | **Software Restriction Policies** | | |
| **14** | **Network Access Protection NAP Client Configuration** | | |
| **15** | **Application Control Policies** | | |
| **16** | **IP Security Policies** | | |
| **17** | **Advanced Audit Policy Configuration** | | |
| **17.1** | **Account Logon** | | |
| 17.1.1 | (L1) Ensure 'Audit Credential Validation' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **17.2** | **Account Management** | | |
| 17.2.1 | (L1) Ensure 'Audit Application Group Management' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.2.2 | (L1) Ensure 'Audit Security Group Management' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.2.3 | (L1) Ensure 'Audit User Account Management' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **17.3** | **Detailed Tracking** | | |
| 17.3.1 | (L1) Ensure 'Audit PNP Activity' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.3.2 | (L1) Ensure 'Audit Process Creation' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **17.4** | **DS Access** | | |
| **17.5** | **Logon/Logoff** | | |
| 17.5.1 | (L1) Ensure 'Audit Account Lockout' is set to include 'Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.5.2 | (L1) Ensure 'Audit Group Membership' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.5.3 | (L1) Ensure 'Audit Logoff' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.5.4 | (L1) Ensure 'Audit Logon' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.5.5 | (L1) Ensure 'Audit Other Logon/Logoff Events' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.5.6 | (L1) Ensure 'Audit Special Logon' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **17.6** | **Object Access** | | |
| 17.6.1 | (L1) Ensure 'Audit Detailed File Share' is set to include 'Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.6.2 | (L1) Ensure 'Audit File Share' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.6.3 | (L1) Ensure 'Audit Other Object Access Events' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.6.4 | (L1) Ensure 'Audit Removable Storage' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **17.7** | **Policy Change** | | |
| 17.7.1 | (L1) Ensure 'Audit Audit Policy Change' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.7.2 | (L1) Ensure 'Audit Authentication Policy Change' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.7.3 | (L1) Ensure 'Audit Authorization Policy Change' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.7.4 | (L1) Ensure 'Audit MPSSVC Rule-Level Policy Change' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.7.5 | (L1) Ensure 'Audit Other Policy Change Events' is set to include 'Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **17.8** | **Privilege Use** | | |
| 17.8.1 | (L1) Ensure 'Audit Sensitive Privilege Use' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **17.9** | **System** | | |
| 17.9.1 | (L1) Ensure 'Audit IPsec Driver' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.9.2 | (L1) Ensure 'Audit Other System Events' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.9.3 | (L1) Ensure 'Audit Security State Change' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.9.4 | (L1) Ensure 'Audit Security System Extension' is set to include 'Success' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 17.9.5 | (L1) Ensure 'Audit System Integrity' is set to 'Success and Failure' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **18** | **Administrative Templates (Computer)** | | |
| **18.1** | **Control Panel** | | |
| **18.1.1** | **Personalization** | | |
| 18.1.1.1 | (L1) Ensure 'Prevent enabling lock screen camera' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.1.1.2 | (L1) Ensure 'Prevent enabling lock screen slide show' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.1.2** | **Regional and Language Options** | | |
| **18.1.2.1** | **Handwriting personalization** | | |
| 18.1.2.2 | (L1) Ensure 'Allow users to enable online speech recognition services' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.1.3 | (L2) Ensure 'Allow Online Tips' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.2** | **Desktop** | | |
| **18.3** | **LAPS** | | |
| 18.3.1 | (L1) Ensure LAPS AdmPwd GPO Extension / CSE is installed (Automated) | :white_large_square: | |
| 18.3.2 | (L1) Ensure 'Do not allow password expiration time longer than required by policy' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - LAPS](<../GP Reports/Windows 11 - LAPS.htm>) |
| 18.3.3 | (L1) Ensure 'Enable Local Admin Password Management' is set to 'Enabled' (Automated) | :white_large_square: | |
| 18.3.4 | (L1) Ensure 'Password Settings: Password Complexity' is set to 'Enabled: Large letters + small letters + numbers + special characters' (Automated) | :ballot_box_with_check: | [Windows 11 - LAPS](<../GP Reports/Windows 11 - LAPS.htm>) |
| 18.3.5 | (L1) Ensure 'Password Settings: Password Length' is set to 'Enabled: 15 or more' (Automated) | :ballot_box_with_check: | [Windows 11 - LAPS](<../GP Reports/Windows 11 - LAPS.htm>) |
| 18.3.6 | (L1) Ensure 'Password Settings: Password Age (Days)' is set to 'Enabled: 30 or fewer' (Automated) | :ballot_box_with_check: | [Windows 11 - LAPS](<../GP Reports/Windows 11 - LAPS.htm>) |
| **18.4** | **MS Security Guide** | | |
| 18.4.1 | (L1) Ensure 'Apply UAC restrictions to local accounts on network logons' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.4.2 | (L1) Ensure 'Configure RPC packet level privacy setting for incoming connections' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.4.3 | (L1) Ensure 'Configure SMB v1 client driver' is set to 'Enabled: Disable driver (recommended)' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.4.4 | (L1) Ensure 'Configure SMB v1 server' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.4.5 | (L1) Ensure 'Enable Structured Exception Handling Overwrite Protection (SEHOP)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.4.6 | (L1) Ensure 'NetBT NodeType configuration' is set to 'Enabled: P-node (recommended)' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.4.7 | (L1) Ensure 'WDigest Authentication' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.5** | **MSS (Legacy)** | | |
| 18.5.1 | (L1) Ensure 'MSS: (AutoAdminLogon) Enable Automatic Logon (not recommended)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.2 | (L1) Ensure 'MSS: (DisableIPSourceRouting IPv6) IP source routing protection level (protects against packet spoofing)' is set to 'Enabled: Highest protection, source routing is completely disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.3 | (L1) Ensure 'MSS: (DisableIPSourceRouting) IP source routing protection level (protects against packet spoofing)' is set to 'Enabled: Highest protection, source routing is completely disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.4 | (L2) Ensure 'MSS: (DisableSavePassword) Prevent the dial-up password from being saved' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.5 | (L1) Ensure 'MSS: (EnableICMPRedirect) Allow ICMP redirects to override OSPF generated routes' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.6 | (L2) Ensure 'MSS: (KeepAliveTime) How often keepalive packets are sent in milliseconds' is set to 'Enabled: 300,000 or 5 minutes (recommended)' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.7 | (L1) Ensure 'MSS: (NoNameReleaseOnDemand) Allow the computer to ignore NetBIOS name release requests except from WINS servers' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.8 | (L2) Ensure 'MSS: (PerformRouterDiscovery) Allow IRDP to detect and configure Default Gateway addresses (could lead to DoS)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.9 | (L1) Ensure 'MSS: (SafeDllSearchMode) Enable Safe DLL search mode (recommended)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.10 | (L1) Ensure 'MSS: (ScreenSaverGracePeriod) The time in seconds before the screen saver grace period expires (0 recommended)' is set to 'Enabled: 5 or fewer seconds' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.11 | (L2) Ensure 'MSS: (TcpMaxDataRetransmissions IPv6) How many times unacknowledged data is retransmitted' is set to 'Enabled: 3' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.12 | (L2) Ensure 'MSS: (TcpMaxDataRetransmissions) How many times unacknowledged data is retransmitted' is set to 'Enabled: 3' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.5.13 | (L1) Ensure 'MSS: (WarningLevel) Percentage threshold for the security event log at which the system will generate a warning' is set to 'Enabled: 90% or less' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6** | **Network** | | |
| **18.6.1** | **Background Intelligent Transfer Service (BITS)** | | |
| **18.6.2** | **BranchCache** | | |
| **18.6.3** | **DirectAccess Client Experience Settings** | | |
| **18.6.4** | **DNS Client** | | |
| 18.6.4.1 | (L1) Ensure 'Configure DNS over HTTPS (DoH) name resolution' is set to 'Enabled: Allow DoH' or higher (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.6.4.2 | (L1) Ensure 'Configure NetBIOS settings' is set to 'Enabled: Disable NetBIOS name resolution on public networks' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.6.4.3 | (L1) Ensure 'Turn off multicast name resolution' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6.5** | **Fonts** | | |
| 18.6.5.1 | (L2) Ensure 'Enable Font Providers' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6.6** | **Hotspot Authentication** | | |
| **18.6.7** | **Lanman Server** | | |
| **18.6.8** | **Lanman Workstation** | | |
| 18.6.8.1 | (L1) Ensure 'Enable insecure guest logons' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6.9** | **Link-Layer Topology Discovery** | | |
| 18.6.9.1 | (L2) Ensure 'Turn on Mapper I/O (LLTDIO) driver' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.6.9.2 | (L2) Ensure 'Turn on Responder (RSPNDR) driver' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6.10** | **Microsoft Peer-to-Peer Networking Services** | | |
| **18.6.10.1** | **Peer Name Resolution Protocol** | | |
| 18.6.10.2 | (L2) Ensure 'Turn off Microsoft Peer-to-Peer Networking Services' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6.11** | **Network Connections** | | |
| **18.6.11.1** | **Windows Defender Firewall (formerly Windows Firewall)** | | |
| 18.6.11.2 | (L1) Ensure 'Prohibit installation and configuration of Network Bridge on your DNS domain network' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.6.11.3 | (L1) Ensure 'Prohibit use of Internet Connection Sharing on your DNS domain network' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.6.11.4 | (L1) Ensure 'Require domain users to elevate when setting a network's location' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6.12** | **Network Connectivity Status Indicator** | | |
| **18.6.13** | **Network Isolation** | | |
| **18.6.14** | **Network Provider** | | |
| 18.6.14.1 | (L1) Ensure 'Hardened UNC Paths' is set to 'Enabled, with "Require Mutual Authentication" and "Require Integrity" set for all NETLOGON and SYSVOL shares' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6.15** | **Offline Files** | | |
| **18.6.16** | **QoS Packet Scheduler** | | |
| **18.6.17** | **SNMP** | | |
| **18.6.18** | **SSL Configuration Settings** | | |
| **18.6.19** | **TCPIP Settings** | | |
| **18.6.19.1** | **IPv6 Transition Technologies** | | |
| **18.6.19.2** | **Parameters** | | |
| 18.6.19.2.1 | (L2) Disable IPv6 (Ensure TCPIP6 Parameter 'DisabledComponents' is set to '0xff (255)') (Automated) | :white_large_square: | |
| **18.6.20** | **Windows Connect Now** | | |
| 18.6.20.1 | (L2) Ensure 'Configuration of wireless settings using Windows Connect Now' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.6.20.2 | (L2) Ensure 'Prohibit access of the Windows Connect Now wizards' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6.21** | **Windows Connection Manager** | | |
| 18.6.21.1 | (L1) Ensure 'Minimize the number of simultaneous connections to the Internet or a Windows Domain' is set to 'Enabled: 3 = Prevent Wi-Fi when on Ethernet' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.6.21.2 | (L1) Ensure 'Prohibit connection to non-domain networks when connected to domain authenticated network' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.6.22** | **Wireless Display** | | |
| **18.6.23** | **WLAN Service** | | |
| **18.6.23.1** | **WLAN Media Cost** | | |
| **18.6.23.2** | **WLAN Settings** | | |
| 18.6.23.2.1 | (L1) Ensure 'Allow Windows to automatically connect to suggested open hotspots, to networks shared by contacts, and to hotspots offering paid services' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.7** | **Printers** | | |
| 18.7.1 | (L1) Ensure 'Allow Print Spooler to accept client connections' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.2 | (L1) Ensure 'Configure Redirection Guard' is set to 'Enabled: Redirection Guard Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.3 | (L1) Ensure 'Configure RPC connection settings: Protocol to use for outgoing RPC connections' is set to 'Enabled: RPC over TCP' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.4 | (L1) Ensure 'Configure RPC connection settings: Use authentication for outgoing RPC connections' is set to 'Enabled: Default' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.5 | (L1) Ensure 'Configure RPC listener settings: Protocols to allow for incoming RPC connections' is set to 'Enabled: RPC over TCP' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.6 | (L1) Ensure 'Configure RPC listener settings: Authentication protocol to use for incoming RPC connections:' is set to 'Enabled: Negotiate' or higher (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.7 | (L1) Ensure 'Configure RPC over TCP port' is set to 'Enabled: 0' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.8 | (L1) Ensure 'Limits print driver installation to Administrators' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.9 | (L1) Ensure 'Manage processing of Queue-specific files' is set to 'Enabled: Limit Queue-specific files to Color profiles' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.10 | (L1) Ensure 'Point and Print Restrictions: When installing drivers for a new connection' is set to 'Enabled: Show warning and elevation prompt' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.7.11 | (L1) Ensure 'Point and Print Restrictions: When updating drivers for an existing connection' is set to 'Enabled: Show warning and elevation prompt' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.8** | **Start Menu and Taskbar** | | |
| **18.8.1** | **Notifications** | | |
| 18.8.1.1 | (L2) Ensure 'Turn off notifications network usage' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.9** | **System** | | |
| **18.9.1** | **Access-Denied Assistance** | | |
| **18.9.2** | **App-V** | | |
| **18.9.3** | **Audit Process Creation** | | |
| 18.9.3.1 | (L1) Ensure 'Include command line in process creation events' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **18.9.4** | **Credentials Delegation** | | |
| 18.9.4.1 | (L1) Ensure 'Encryption Oracle Remediation' is set to 'Enabled: Force Updated Clients' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.4.2 | (L1) Ensure 'Remote host allows delegation of nonexportable credentials' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.5** | **Device Guard** | | |
| 18.9.5.1 | (L1) Ensure 'Turn On Virtualization Based Security' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Virtualization Based Security](<../GP Reports/Windows 11 - Virtualization Based Security.htm>) |
| 18.9.5.2 | (L1) Ensure 'Turn On Virtualization Based Security: Select Platform Security Level' is set to 'Secure Boot' or higher (Automated) | :ballot_box_with_check: | [Windows 11 - Virtualization Based Security](<../GP Reports/Windows 11 - Virtualization Based Security.htm>) |
| 18.9.5.3 | (L1) Ensure 'Turn On Virtualization Based Security: Virtualization Based Protection of Code Integrity' is set to 'Enabled with UEFI lock' (Automated) | :ballot_box_with_check: | [Windows 11 - Virtualization Based Security](<../GP Reports/Windows 11 - Virtualization Based Security.htm>) |
| 18.9.5.4 | (L1) Ensure 'Turn On Virtualization Based Security: Require UEFI Memory Attributes Table' is set to 'True (checked)' (Automated) | :ballot_box_with_check: | [Windows 11 - Virtualization Based Security](<../GP Reports/Windows 11 - Virtualization Based Security.htm>) |
| 18.9.5.5 | (L1) Ensure 'Turn On Virtualization Based Security: Credential Guard Configuration' is set to 'Enabled with UEFI lock' (Automated) | :ballot_box_with_check: | [Windows 11 - Virtualization Based Security](<../GP Reports/Windows 11 - Virtualization Based Security.htm>) |
| 18.9.5.6 | (L1) Ensure 'Turn On Virtualization Based Security: Secure Launch Configuration' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Virtualization Based Security](<../GP Reports/Windows 11 - Virtualization Based Security.htm>) |
| 18.9.5.7 | (L1) Ensure 'Turn On Virtualization Based Security: Kernel-mode Hardware-enforced Stack Protection' is set to 'Enabled: Enabled in enforcement mode' (Automated) | :ballot_box_with_check: | [Windows 11 - Virtualization Based Security](<../GP Reports/Windows 11 - Virtualization Based Security.htm>) |
| **18.9.6** | **Device Health Attestation Service** | | |
| **18.9.7** | **Device Installation** | | |
| **18.9.7.1** | **Device Installation Restrictions** | | |
| 18.9.7.1.1 | (BL) Ensure 'Prevent installation of devices that match any of these device IDs' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.9.7.1.2 | (BL) Ensure 'Prevent installation of devices that match any of these device IDs: Prevent installation of devices that match any of these device IDs' is set to 'PCI\CC_0C0A' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.9.7.1.3 | (BL) Ensure 'Prevent installation of devices that match any of these device IDs: Also apply to matching devices that are already installed.' is set to 'True' (checked) (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.9.7.1.4 | (BL) Ensure 'Prevent installation of devices using drivers that match these device setup classes' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.9.7.1.5 | (BL) Ensure 'Prevent installation of devices using drivers that match these device setup classes: Prevent installation of devices using drivers for these device setup' is set to 'IEEE 1394 device setup classes' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.9.7.1.6 | (BL) Ensure 'Prevent installation of devices using drivers that match these device setup classes: Also apply to matching devices that are already installed.' is set to 'True' (checked) (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.9.7.2 | (L1) Ensure 'Prevent device metadata retrieval from the Internet' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.8** | **Disk NV Cache** | | |
| **18.9.9** | **Disk Quotas** | | |
| **18.9.10** | **Display** | | |
| **18.9.11** | **Distributed COM** | | |
| **18.9.12** | **Driver Installation** | | |
| **18.9.13** | **Early Launch Antimalware** | | |
| 18.9.13.1 | (L1) Ensure 'Boot-Start Driver Initialization Policy' is set to 'Enabled: Good, unknown and bad but critical' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.9.14** | **Enhanced Storage Access** | | |
| **18.9.15** | **File Classification Infrastructure** | | |
| **18.9.16** | **File Share Shadow Copy Provider** | | |
| **18.9.17** | **Filesystem (formerly NTFS Filesystem)** | | |
| **18.9.18** | **Folder Redirection** | | |
| **18.9.19** | **Group Policy** | | |
| **18.9.19.1** | **Logging and tracing** | | |
| 18.9.19.2 | (L1) Ensure 'Configure registry policy processing: Do not apply during periodic background processing' is set to 'Enabled: FALSE' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.19.3 | (L1) Ensure 'Configure registry policy processing: Process even if the Group Policy objects have not changed' is set to 'Enabled: TRUE' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.19.4 | (L1) Ensure 'Continue experiences on this device' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.19.5 | (L1) Ensure 'Turn off background refresh of Group Policy' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.20** | **Internet Communication Management** | | |
| **18.9.20.1** | **Internet Communication settings** | | |
| 18.9.20.1.1 | (L2) Ensure 'Turn off access to the Store' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.20.1.2 | (L1) Ensure 'Turn off downloading of print drivers over HTTP' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.20.1.3 | (L2) Ensure 'Turn off handwriting personalization data sharing' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.4 | (L2) Ensure 'Turn off handwriting recognition error reporting' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.5 | (L2) Ensure 'Turn off Internet Connection Wizard if URL connection is referring to Microsoft.com' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.6 | (L1) Ensure 'Turn off Internet download for Web publishing and online ordering wizards' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.7 | (L2) Ensure 'Turn off printing over HTTP' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.20.1.8 | (L2) Ensure 'Turn off Registration if URL connection is referring to Microsoft.com' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.9 | (L2) Ensure 'Turn off Search Companion content file updates' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.10 | (L2) Ensure 'Turn off the "Order Prints" picture task' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.11 | (L2) Ensure 'Turn off the "Publish to Web" task for files and folders' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.12 | (L2) Ensure 'Turn off the Windows Messenger Customer Experience Improvement Program' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.13 | (L2) Ensure 'Turn off Windows Customer Experience Improvement Program' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.20.1.14 | (L2) Ensure 'Turn off Windows Error Reporting' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.9.21** | **iSCSI** | | |
| **18.9.22** | **KDC** | | |
| **18.9.23** | **Kerberos** | | |
| 18.9.23.1 | (L2) Ensure 'Support device authentication using certificate' is set to 'Enabled: Automatic' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.24** | **Kernel DMA Protection** | | |
| 18.9.24.1 | (BL) Ensure 'Enumeration policy for external devices incompatible with Kernel DMA Protection' is set to 'Enabled: Block All' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.25** | **Local Security Authority** | | |
| 18.9.25.1 | (L1) Ensure 'Allow Custom SSPs and APs to be loaded into LSASS' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.25.2 | (L1) Ensure 'Configures LSASS to run as a protected process' is set to 'Enabled: Enabled with UEFI Lock' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.26** | **Locale Services** | | |
| 18.9.26.1 | (L2) Ensure 'Disallow copying of user input methods to the system account for sign-in' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.27** | **Logon** | | |
| 18.9.27.1 | (L1) Ensure 'Block user from showing account details on sign-in' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.27.2 | (L1) Ensure 'Do not display network selection UI' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.27.3 | (L1) Ensure 'Do not enumerate connected users on domain-joined computers' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.27.4 | (L1) Ensure 'Enumerate local users on domain-joined computers' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.27.5 | (L1) Ensure 'Turn off app notifications on the lock screen' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.27.6 | (L1) Ensure 'Turn off picture password sign-in' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.27.7 | (L1) Ensure 'Turn on convenience PIN sign-in' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.28** | **Mitigation Options** | | |
| **18.9.29** | **Net Logon** | | |
| **18.9.30** | **OS Policies** | | |
| 18.9.30.1 | (L2) Ensure 'Allow Clipboard synchronization across devices' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.30.2 | (L2) Ensure 'Allow upload of User Activities' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.9.31** | **PIN Complexity** | | |
| **18.9.32** | **Power Management** | | |
| **18.9.32.1** | **Button Settings** | | |
| **18.9.32.2** | **Energy Saver Settings** | | |
| **18.9.32.3** | **Hard Disk Settings** | | |
| **18.9.32.4** | **Notification Settings** | | |
| **18.9.32.5** | **Power Throttling Settings** | | |
| **18.9.32.6** | **Sleep Settings** | | |
| 18.9.32.6.1 | (L1) Ensure 'Allow network connectivity during connected-standby (on battery)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.32.6.2 | (L1) Ensure 'Allow network connectivity during connected-standby (plugged in)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.32.6.3 | (BL) Ensure 'Allow standby states (S1-S3) when sleeping (on battery)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.9.32.6.4 | (BL) Ensure 'Allow standby states (S1-S3) when sleeping (plugged in)' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.9.32.6.5 | (L1) Ensure 'Require a password when a computer wakes (on battery)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.32.6.6 | (L1) Ensure 'Require a password when a computer wakes (plugged in)' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.33** | **Recovery** | | |
| **18.9.34** | **Remote Assistance** | | |
| 18.9.34.1 | (L1) Ensure 'Configure Offer Remote Assistance' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.9.34.2 | (L1) Ensure 'Configure Solicited Remote Assistance' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.9.35** | **Remote Procedure Call** | | |
| 18.9.35.1 | (L1) Ensure 'Enable RPC Endpoint Mapper Client Authentication' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.9.35.2 | (L1) Ensure 'Restrict Unauthenticated RPC clients' is set to 'Enabled: Authenticated' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.9.36** | **Removable Storage Access** | | |
| **18.9.37** | **Scripts** | | |
| **18.9.38** | **Security Account Manager** | | |
| **18.9.39** | **Server Manager** | | |
| **18.9.40** | **Service Control Manager Settings** | | |
| **18.9.41** | **Shutdown** | | |
| **18.9.42** | **Shutdown Options** | | |
| **18.9.43** | **Storage Health** | | |
| **18.9.44** | **Storage Sense** | | |
| **18.9.45** | **System Restore** | | |
| **18.9.46** | **Troubleshooting and Diagnostics** | | |
| **18.9.46.1** | **Application Compatibility Diagnostics** | | |
| **18.9.46.2** | **Corrupted File Recovery** | | |
| **18.9.46.3** | **Disk Diagnostic** | | |
| **18.9.46.4** | **Fault Tolerant Heap** | | |
| **18.9.46.5** | **Microsoft Support Diagnostic Tool** | | |
| 18.9.46.5.1 | (L2) Ensure 'Microsoft Support Diagnostic Tool: Turn on MSDT interactive communication with support provider' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.9.46.6** | **MSI Corrupted File Recovery** | | |
| **18.9.46.7** | **Scheduled Maintenance** | | |
| **18.9.46.8** | **Scripted Diagnostics** | | |
| **18.9.46.9** | **Windows Boot Performance Diagnostics** | | |
| **18.9.46.10** | **Windows Memory Leak Diagnosis** | | |
| **18.9.46.11** | **Windows Performance PerfTrack** | | |
| 18.9.46.11.1 | (L2) Ensure 'Enable/Disable PerfTrack' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.9.47** | **Trusted Platform Module Services** | | |
| **18.9.48** | **User Profiles** | | |
| 18.9.48.1 | (L2) Ensure 'Turn off the advertising ID' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.9.49** | **Windows File Protection** | | |
| **18.9.50** | **Windows Time Service** | | |
| **18.9.50.1** | **Time Providers** | | |
| 18.9.50.1.1 | (L2) Ensure 'Enable Windows NTP Client' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [NTP Service - Client](<../GP Reports/NTP Service - Client.htm>) |
| 18.9.50.1.2 | (L2) Ensure 'Enable Windows NTP Server' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [NTP Service - Client](<../GP Reports/NTP Service - Client.htm>) |
| **18.10** | **Windows Components** | | |
| **18.10.1** | **ActiveX Installer Service** | | |
| **18.10.2** | **Add features to Windows 10 (formerly Windows Anytime Upgrade)** | | |
| **18.10.3** | **App Package Deployment** | | |
| 18.10.3.1 | (L2) Ensure 'Allow a Windows app to share application data between users' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.3.2 | (L1) Ensure 'Prevent non-admin users from installing packaged Windows apps' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.4** | **App Privacy** | | |
| 18.10.4.1 | (L1) Ensure 'Let Windows apps activate with voice while the system is locked' is set to 'Enabled: Force Deny' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.10.5** | **App runtime** | | |
| 18.10.5.1 | (L1) Ensure 'Allow Microsoft accounts to be optional' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| 18.10.5.2 | (L2) Ensure 'Block launching Universal Windows apps with Windows Runtime API access from hosted content.' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.6** | **Application Compatibility** | | |
| **18.10.7** | **AutoPlay Policies** | | |
| 18.10.7.1 | (L1) Ensure 'Disallow Autoplay for non-volume devices' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.7.2 | (L1) Ensure 'Set the default behavior for AutoRun' is set to 'Enabled: Do not execute any autorun commands' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.7.3 | (L1) Ensure 'Turn off Autoplay' is set to 'Enabled: All drives' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.8** | **Biometrics** | | |
| **18.10.8.1** | **Facial Features** | | |
| 18.10.8.1.1 | (L1) Ensure 'Configure enhanced anti-spoofing' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.9** | **BitLocker Drive Encryption** | | |
| **18.10.9.1** | **Fixed Data Drives** | | |
| 18.10.9.1.1 | (BL) Ensure 'Allow access to BitLocker-protected fixed data drives from earlier versions of Windows' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.2 | (BL) Ensure 'Choose how BitLocker-protected fixed drives can be recovered' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.3 | (BL) Ensure 'Choose how BitLocker-protected fixed drives can be recovered: Allow data recovery agent' is set to 'Enabled: True' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.4 | (BL) Ensure 'Choose how BitLocker-protected fixed drives can be recovered: Recovery Password' is set to 'Enabled: Allow 48-digit recovery password' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.5 | (BL) Ensure 'Choose how BitLocker-protected fixed drives can be recovered: Recovery Key' is set to 'Enabled: Allow 256-bit recovery key' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.6 | (BL) Ensure 'Choose how BitLocker-protected fixed drives can be recovered: Omit recovery options from the BitLocker setup wizard' is set to 'Enabled: True' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.7 | (BL) Ensure 'Choose how BitLocker-protected fixed drives can be recovered: Save BitLocker recovery information to AD DS for fixed data drives' is set to 'Enabled: False' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.8 | (BL) Ensure 'Choose how BitLocker-protected fixed drives can be recovered: Configure storage of BitLocker recovery information to AD DS' is set to 'Enabled: Backup recovery passwords and key packages' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.9 | (BL) Ensure 'Choose how BitLocker-protected fixed drives can be recovered: Do not enable BitLocker until recovery information is stored to AD DS for fixed data drives' is set to 'Enabled: False' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.10 | (BL) Ensure 'Configure use of hardware-based encryption for fixed data drives' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.11 | (BL) Ensure 'Configure use of passwords for fixed data drives' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.12 | (BL) Ensure 'Configure use of smart cards on fixed data drives' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.1.13 | (BL) Ensure 'Configure use of smart cards on fixed data drives: Require use of smart cards on fixed data drives' is set to 'Enabled: True' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| **18.10.9.2** | **Operating System Drives** | | |
| 18.10.9.2.1 | (BL) Ensure 'Allow enhanced PINs for startup' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.2 | (BL) Ensure 'Allow Secure Boot for integrity validation' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.3 | (BL) Ensure 'Choose how BitLocker-protected operating system drives can be recovered' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.4 | (BL) Ensure 'Choose how BitLocker-protected operating system drives can be recovered: Allow data recovery agent' is set to 'Enabled: False' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.5 | (BL) Ensure 'Choose how BitLocker-protected operating system drives can be recovered: Recovery Password' is set to 'Enabled: Require 48-digit recovery password' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.6 | (BL) Ensure 'Choose how BitLocker-protected operating system drives can be recovered: Recovery Key' is set to 'Enabled: Do not allow 256-bit recovery key' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.7 | (BL) Ensure 'Choose how BitLocker-protected operating system drives can be recovered: Omit recovery options from the BitLocker setup wizard' is set to 'Enabled: True' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.8 | (BL) Ensure 'Choose how BitLocker-protected operating system drives can be recovered: Save BitLocker recovery information to AD DS for operating system drives' is set to 'Enabled: True' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.9 | (BL) Ensure 'Choose how BitLocker-protected operating system drives can be recovered: Configure storage of BitLocker recovery information to AD DS:' is set to 'Enabled: Store recovery passwords and key packages' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.10 | (BL) Ensure 'Choose how BitLocker-protected operating system drives can be recovered: Do not enable BitLocker until recovery information is stored to AD DS for operating system drives' is set to 'Enabled: True' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.11 | (BL) Ensure 'Configure use of hardware-based encryption for operating system drives' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.12 | (BL) Ensure 'Configure use of passwords for operating system drives' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.13 | (BL) Ensure 'Require additional authentication at startup' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.2.14 | (BL) Ensure 'Require additional authentication at startup: Allow BitLocker without a compatible TPM' is set to 'Enabled: False' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| **18.10.9.3** | **Removable Data Drives** | | |
| 18.10.9.3.1 | (BL) Ensure 'Allow access to BitLocker-protected removable data drives from earlier versions of Windows' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.2 | (BL) Ensure 'Choose how BitLocker-protected removable drives can be recovered' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.3 | (BL) Ensure 'Choose how BitLocker-protected removable drives can be recovered: Allow data recovery agent' is set to 'Enabled: True' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.4 | (BL) Ensure 'Choose how BitLocker-protected removable drives can be recovered: Recovery Password' is set to 'Enabled: Do not allow 48-digit recovery password' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.5 | (BL) Ensure 'Choose how BitLocker-protected removable drives can be recovered: Recovery Key' is set to 'Enabled: Do not allow 256-bit recovery key' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.6 | (BL) Ensure 'Choose how BitLocker-protected removable drives can be recovered: Omit recovery options from the BitLocker setup wizard' is set to 'Enabled: True' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.7 | (BL) Ensure 'Choose how BitLocker-protected removable drives can be recovered: Save BitLocker recovery information to AD DS for removable data drives' is set to 'Enabled: False' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.8 | (BL) Ensure 'Choose how BitLocker-protected removable drives can be recovered: Configure storage of BitLocker recovery information to AD DS:' is set to 'Enabled: Backup recovery passwords and key packages' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.9 | (BL) Ensure 'Choose how BitLocker-protected removable drives can be recovered: Do not enable BitLocker until recovery information is stored to AD DS for removable data drives' is set to 'Enabled: False' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.10 | (BL) Ensure 'Configure use of hardware-based encryption for removable data drives' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.11 | (BL) Ensure 'Configure use of passwords for removable data drives' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.12 | (BL) Ensure 'Configure use of smart cards on removable data drives' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.13 | (BL) Ensure 'Configure use of smart cards on removable data drives: Require use of smart cards on removable data drives' is set to 'Enabled: True' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.14 | (BL) Ensure 'Deny write access to removable drives not protected by BitLocker' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.3.15 | (BL) Ensure 'Deny write access to removable drives not protected by BitLocker: Do not allow write access to devices configured in another organization' is set to 'Enabled: False' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| 18.10.9.4 | (BL) Ensure 'Disable new DMA devices when this computer is locked' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - BitLocker](<../GP Reports/Windows 11 - BitLocker.htm>) |
| **18.10.10** | **Camera** | | |
| 18.10.10.1 | (L2) Ensure 'Allow Use of Camera' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.11** | **Chat** | | |
| **18.10.12** | **Cloud Content** | | |
| 18.10.12.1 | (L1) Ensure 'Turn off cloud consumer account state content' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.12.2 | (L2) Ensure 'Turn off cloud optimized content' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.12.3 | (L1) Ensure 'Turn off Microsoft consumer experiences' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.10.13** | **Connect** | | |
| 18.10.13.1 | (L1) Ensure 'Require pin for pairing' is set to 'Enabled: First Time' OR 'Enabled: Always' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.14** | **Credential User Interface** | | |
| 18.10.14.1 | (L1) Ensure 'Do not display the password reveal button' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.14.2 | (L1) Ensure 'Enumerate administrator accounts on elevation' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.14.3 | (L1) Ensure 'Prevent the use of security questions for local accounts' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.15** | **Data Collection and Preview Builds** | | |
| 18.10.15.1 | (L1) Ensure 'Allow Diagnostic Data' is set to 'Enabled: Diagnostic data off (not recommended)' or 'Enabled: Send required diagnostic data' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.15.2 | (L2) Ensure 'Configure Authenticated Proxy usage for the Connected User Experience and Telemetry service' is set to 'Enabled: Disable Authenticated Proxy usage' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.15.3 | (L1) Ensure 'Disable OneSettings Downloads' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.15.4 | (L1) Ensure 'Do not show feedback notifications' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.15.5 | (L1) Ensure 'Enable OneSettings Auditing' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.15.6 | (L1) Ensure 'Limit Diagnostic Log Collection' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.15.7 | (L1) Ensure 'Limit Dump Collection' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.15.8 | (L1) Ensure 'Toggle user control over Insider builds' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.10.16** | **Delivery Optimization** | | |
| 18.10.16.1 | (L1) Ensure 'Download Mode' is NOT set to 'Enabled: Internet' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.17** | **Desktop App Installer** | | |
| 18.10.17.1 | (L1) Ensure 'Enable App Installer' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.17.2 | (L1) Ensure 'Enable App Installer Experimental Features' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.17.3 | (L1) Ensure 'Enable App Installer Hash Override' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.17.4 | (L1) Ensure 'Enable App Installer ms-appinstaller protocol' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.18** | **Desktop Gadgets** | | |
| **18.10.19** | **Desktop Window Manager** | | |
| **18.10.20** | **Device and Driver Compatibility** | | |
| **18.10.21** | **Device Registration (formerly Workplace Join)** | | |
| **18.10.22** | **Digital Locker** | | |
| **18.10.23** | **Edge UI** | | |
| **18.10.24** | **EMET** | | |
| **18.10.25** | **Event Forwarding** | | |
| **18.10.26** | **Event Log Service** | | |
| **18.10.26.1** | **Application** | | |
| 18.10.26.1.1 | (L1) Ensure 'Application: Control Event Log behavior when the log file reaches its maximum size' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 18.10.26.1.2 | (L1) Ensure 'Application: Specify the maximum log file size (KB)' is set to 'Enabled: 32,768 or greater' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **18.10.26.2** | **Security** | | |
| 18.10.26.2.1 | (L1) Ensure 'Security: Control Event Log behavior when the log file reaches its maximum size' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 18.10.26.2.2 | (L1) Ensure 'Security: Specify the maximum log file size (KB)' is set to 'Enabled: 196,608 or greater' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **18.10.26.3** | **Setup** | | |
| 18.10.26.3.1 | (L1) Ensure 'Setup: Control Event Log behavior when the log file reaches its maximum size' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 18.10.26.3.2 | (L1) Ensure 'Setup: Specify the maximum log file size (KB)' is set to 'Enabled: 32,768 or greater' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **18.10.26.4** | **System** | | |
| 18.10.26.4.1 | (L1) Ensure 'System: Control Event Log behavior when the log file reaches its maximum size' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 18.10.26.4.2 | (L1) Ensure 'System: Specify the maximum log file size (KB)' is set to 'Enabled: 32,768 or greater' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| **18.10.27** | **Event Logging** | | |
| **18.10.28** | **Event Viewer** | | |
| **18.10.29** | **File Explorer (formerly Windows Explorer)** | | |
| **18.10.29.1** | **Previous Versions** | | |
| 18.10.29.2 | (L1) Ensure 'Turn off Data Execution Prevention for Explorer' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.29.3 | (L2) Ensure 'Turn off files from Office.com in Quick access view' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.29.4 | (L1) Ensure 'Turn off heap termination on corruption' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.29.5 | (L1) Ensure 'Turn off shell protocol protected mode' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.30** | **File History** | | |
| **18.10.31** | **Find My Device** | | |
| **18.10.32** | **Handwriting** | | |
| **18.10.33** | **HomeGroup** | | |
| 18.10.33.1 | (L1) Ensure 'Prevent the computer from joining a homegroup' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.34** | **Human Presence** | | |
| **18.10.35** | **Internet Explorer** | | |
| **18.10.36** | **Internet Information Services** | | |
| **18.10.37** | **Location and Sensors** | | |
| **18.10.37.1** | **Windows Location Provider** | | |
| 18.10.37.2 | (L2) Ensure 'Turn off location' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.10.38** | **Maintenance Scheduler** | | |
| **18.10.39** | **Maps** | | |
| **18.10.40** | **MDM** | | |
| **18.10.41** | **Messaging** | | |
| 18.10.41.1 | (L2) Ensure 'Allow Message Service Cloud Sync' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.10.42** | **Microsoft account** | | |
| 18.10.42.1 | (L1) Ensure 'Block all consumer Microsoft account user authentication' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Domain Security](<../GP Reports/Domain Security.htm>) |
| **18.10.43** | **Microsoft Defender Antivirus (formerly Windows Defender and Windows Defender Antivirus)** | | |
| **18.10.43.1** | **Client Interface** | | |
| **18.10.43.2** | **Device Control** | | |
| **18.10.43.3** | **Exclusions** | | |
| **18.10.43.4** | **Features** | | |
| **18.10.43.5** | **MAPS** | | |
| 18.10.43.5.1 | (L1) Ensure 'Configure local setting override for reporting to Microsoft MAPS' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.43.5.2 | (L2) Ensure 'Join Microsoft MAPS' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.10.43.6** | **Microsoft Defender Exploit Guard (formerly Windows Defender Exploit Guard)** | | |
| **18.10.43.6.1** | **Attack Surface Reduction** | | |
| 18.10.43.6.1.1 | (L1) Ensure 'Configure Attack Surface Reduction rules' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.43.6.1.2 | (L1) Ensure 'Configure Attack Surface Reduction rules: Set the state for each ASR rule' is configured (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.43.6.2** | **Controlled Folder Access** | | |
| **18.10.43.6.3** | **Network Protection** | | |
| 18.10.43.6.3.1 | (L1) Ensure 'Prevent users and apps from accessing dangerous websites' is set to 'Enabled: Block' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.43.7** | **MpEngine** | | |
| 18.10.43.7.1 | (L2) Ensure 'Enable file hash computation feature' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.43.8** | **Network Inspection System** | | |
| **18.10.43.9** | **Quarantine** | | |
| **18.10.43.10** | **Real-time Protection** | | |
| 18.10.43.10.1 | (L1) Ensure 'Scan all downloaded files and attachments' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.43.10.2 | (L1) Ensure 'Turn off real-time protection' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.43.10.3 | (L1) Ensure 'Turn on behavior monitoring' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.43.10.4 | (L1) Ensure 'Turn on script scanning' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.43.11** | **Remediation** | | |
| **18.10.43.12** | **Reporting** | | |
| 18.10.43.12.1 | (L2) Ensure 'Configure Watson events' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.10.43.13** | **Scan** | | |
| 18.10.43.13.1 | (L1) Ensure 'Scan removable drives' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.43.13.2 | (L1) Ensure 'Turn on e-mail scanning' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.43.14** | **Security Intelligence Updates (formerly Signature Updates)** | | |
| **18.10.43.15** | **Threats** | | |
| 18.10.43.16 | (L1) Ensure 'Configure detection for potentially unwanted applications' is set to 'Enabled: Block' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.43.17 | (L1) Ensure 'Turn off Microsoft Defender AntiVirus' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.44** | **Microsoft Defender Application Guard (formerly Windows Defender Application Guard)** | | |
| 18.10.44.1 | (L1) Ensure 'Allow auditing events in Microsoft Defender Application Guard' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.44.2 | (L1) Ensure 'Allow camera and microphone access in Microsoft Defender Application Guard' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.44.3 | (L1) Ensure 'Allow data persistence for Microsoft Defender Application Guard' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.44.4 | (L1) Ensure 'Allow files to download and save to the host operating system from Microsoft Defender Application Guard' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.44.5 | (L1) Ensure 'Configure Microsoft Defender Application Guard clipboard settings: Clipboard behavior setting' is set to 'Enabled: Enable clipboard operation from an isolated session to the host' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.44.6 | (L1) Ensure 'Turn on Microsoft Defender Application Guard in Managed Mode' is set to 'Enabled: 1' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.45** | **Microsoft Defender Exploit Guard (formerly Windows Defender Exploit Guard)** | | |
| **18.10.46** | **Microsoft Edge** | | |
| **18.10.47** | **Microsoft Secondary Authentication Factor** | | |
| **18.10.48** | **Microsoft User Experience Virtualization** | | |
| **18.10.49** | **NetMeeting** | | |
| **18.10.50** | **News and interests** | | |
| 18.10.50.1 | (L2) Ensure 'Enable news and interests on the taskbar' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.10.51** | **OneDrive (formerly SkyDrive)** | | |
| 18.10.51.1 | (L1) Ensure 'Prevent the usage of OneDrive for file storage' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.52** | **Online Assistance** | | |
| **18.10.53** | **OOBE** | | |
| **18.10.54** | **Portable Operating System** | | |
| **18.10.55** | **Presentation Settings** | | |
| **18.10.56** | **Push To Install** | | |
| 18.10.56.1 | (L2) Ensure 'Turn off Push To Install service' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.57** | **Remote Desktop Services (formerly Terminal Services)** | | |
| **18.10.57.1** | **RD Licensing (formerly TS Licensing)** | | |
| **18.10.57.2** | **Remote Desktop Connection Client** | | |
| **18.10.57.2.1** | **RemoteFX USB Device Redirection** | | |
| 18.10.57.2.2 | (L2) Ensure 'Disable Cloud Clipboard integration for server-to-client data transfer' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.2.3 | (L1) Ensure 'Do not allow passwords to be saved' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| **18.10.57.3** | **Remote Desktop Session Host (formerly Terminal Server)** | | |
| **18.10.57.3.1** | **Application Compatibility** | | |
| **18.10.57.3.2** | **Connections** | | |
| 18.10.57.3.2.1 | (L2) Ensure 'Allow users to connect remotely by using Remote Desktop Services' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.57.3.3** | **Device and Resource Redirection** | | |
| 18.10.57.3.3.1 | (L2) Ensure 'Allow UI Automation redirection' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.3.2 | (L2) Ensure 'Do not allow COM port redirection' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.3.3 | (L1) Ensure 'Do not allow drive redirection' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.3.4 | (L2) Ensure 'Do not allow location redirection' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.3.5 | (L2) Ensure 'Do not allow LPT port redirection' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.3.6 | (L2) Ensure 'Do not allow supported Plug and Play device redirection' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.3.7 | (L2) Ensure 'Do not allow WebAuthn redirection' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| **18.10.57.3.4** | **Licensing** | | |
| **18.10.57.3.5** | **Printer Redirection** | | |
| **18.10.57.3.6** | **Profiles** | | |
| **18.10.57.3.7** | **RD Connection Broker (formerly TS Connection Broker)** | | |
| **18.10.57.3.8** | **Remote Session Environment** | | |
| **18.10.57.3.9** | **Security** | | |
| 18.10.57.3.9.1 | (L1) Ensure 'Always prompt for password upon connection' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.9.2 | (L1) Ensure 'Require secure RPC communication' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.9.3 | (L1) Ensure 'Require use of specific security layer for remote (RDP) connections' is set to 'Enabled: SSL' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.9.4 | (L1) Ensure 'Require user authentication for remote connections by using Network Level Authentication' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.9.5 | (L1) Ensure 'Set client connection encryption level' is set to 'Enabled: High Level' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| **18.10.57.3.10** | **Session Time Limits** | | |
| 18.10.57.3.10.1 | (L2) Ensure 'Set time limit for active but idle Remote Desktop Services sessions' is set to 'Enabled: 15 minutes or less, but not Never (0)' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| 18.10.57.3.10.2 | (L2) Ensure 'Set time limit for disconnected sessions' is set to 'Enabled: 1 minute' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| **18.10.57.3.11** | **Temporary folders** | | |
| 18.10.57.3.11.1 | (L1) Ensure 'Do not delete temp folders upon exit' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Remote Desktop Service](<../GP Reports/Remote Desktop Service.htm>) |
| **18.10.58** | **RSS Feeds** | | |
| 18.10.58.1 | (L1) Ensure 'Prevent downloading of enclosures' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.59** | **Search** | | |
| **18.10.59.1** | **OCR** | | |
| 18.10.59.2 | (L2) Ensure 'Allow Cloud Search' is set to 'Enabled: Disable Cloud Search' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.59.3 | (L1) Ensure 'Allow Cortana' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.59.4 | (L1) Ensure 'Allow Cortana above lock screen' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.59.5 | (L1) Ensure 'Allow indexing of encrypted files' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.59.6 | (L1) Ensure 'Allow search and Cortana to use location' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| 18.10.59.7 | (L2) Ensure 'Allow search highlights' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.60** | **Security Center** | | |
| **18.10.61** | **Shutdown Options** | | |
| **18.10.62** | **Smart Card** | | |
| **18.10.63** | **Software Protection Platform** | | |
| 18.10.63.1 | (L2) Ensure 'Turn off KMS Client Online AVS Validation' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - Computer](<../GP Reports/Diagnostics and Reporting - Computer.htm>) |
| **18.10.64** | **Sound Recorder** | | |
| **18.10.65** | **Speech** | | |
| **18.10.66** | **Store** | | |
| 18.10.66.1 | (L2) Ensure 'Disable all apps from Microsoft Store' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.66.2 | (L1) Ensure 'Only display the private store within the Microsoft Store' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.66.3 | (L1) Ensure 'Turn off Automatic Download and Install of updates' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.66.4 | (L1) Ensure 'Turn off the offer to update to the latest version of Windows' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.66.5 | (L2) Ensure 'Turn off the Store application' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.67** | **Sync your settings** | | |
| **18.10.68** | **Tablet PC** | | |
| **18.10.69** | **Task Scheduler** | | |
| **18.10.70** | **Tenant Restrictions** | | |
| **18.10.71** | **Text Input** | | |
| **18.10.72** | **Widgets** | | |
| 18.10.72.1 | (L1) Ensure 'Allow widgets' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.73** | **Windows Calendar** | | |
| **18.10.74** | **Windows Color System** | | |
| **18.10.75** | **Windows Customer Experience Improvement Program** | | |
| **18.10.76** | **Windows Defender SmartScreen** | | |
| **18.10.76.1** | **Enhanced Phishing Protection** | | |
| 18.10.76.1.1 | (L1) Ensure 'Notify Malicious' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.76.1.2 | (L1) Ensure 'Notify Password Reuse' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.76.1.3 | (L1) Ensure 'Notify Unsafe App' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.76.1.4 | (L1) Ensure 'Service Enabled' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.76.2** | **Explorer** | | |
| 18.10.76.2.1 | (L1) Ensure 'Configure Windows Defender SmartScreen' is set to 'Enabled: Warn and prevent bypass' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.76.3** | **Microsoft Edge** | | |
| 18.10.76.3.1 | (L1) Ensure 'Configure Windows Defender SmartScreen' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| 18.10.76.3.2 | (L1) Ensure 'Prevent bypassing Windows Defender SmartScreen prompts for sites' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Defender Antivirus (NG)](<../GP Reports/Windows Defender Antivirus (NG).htm>) |
| **18.10.77** | **Windows Error Reporting** | | |
| **18.10.78** | **Windows Game Recording and Broadcasting** | | |
| 18.10.78.1 | (L1) Ensure 'Enables or disables Windows Game Recording and Broadcasting' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.79** | **Windows Hello for Business (formerly Microsoft Passport for Work)** | | |
| 18.10.79.1 | (L1) Ensure 'Enable ESS with Supported Peripherals' is set to 'Enabled: 1' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.80** | **Windows Ink Workspace** | | |
| 18.10.80.1 | (L2) Ensure 'Allow suggested apps in Windows Ink Workspace' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.80.2 | (L1) Ensure 'Allow Windows Ink Workspace' is set to 'Enabled: On, but disallow access above lock' OR 'Enabled: Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.81** | **Windows Installer** | | |
| 18.10.81.1 | (L1) Ensure 'Allow user control over installs' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.81.2 | (L1) Ensure 'Always install with elevated privileges' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.81.3 | (L2) Ensure 'Prevent Internet Explorer security prompt for Windows Installer scripts' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.82** | **Windows Logon Options** | | |
| 18.10.82.1 | (L1) Ensure 'Enable MPR notifications for the system' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.82.2 | (L1) Ensure 'Sign-in and lock last interactive user automatically after a restart' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.83** | **Windows Media Digital Rights Management** | | |
| **18.10.84** | **Windows Media Player** | | |
| **18.10.85** | **Windows Messenger** | | |
| **18.10.86** | **Windows Mobility Center** | | |
| **18.10.87** | **Windows PowerShell** | | |
| 18.10.87.1 | (L1) Ensure 'Turn on PowerShell Script Block Logging' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Audit](<../GP Reports/Windows 11 - Audit.htm>) |
| 18.10.87.2 | (L1) Ensure 'Turn on PowerShell Transcription' is set to 'Enabled' (Automated) | :white_large_square: | |
| **18.10.88** | **Windows Reliability Analysis** | | |
| **18.10.89** | **Windows Remote Management (WinRM)** | | |
| **18.10.89.1** | **WinRM Client** | | |
| 18.10.89.1.1 | (L1) Ensure 'Allow Basic authentication' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Remote Management](<../GP Reports/Windows Remote Management.htm>) |
| 18.10.89.1.2 | (L1) Ensure 'Allow unencrypted traffic' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Remote Management](<../GP Reports/Windows Remote Management.htm>) |
| 18.10.89.1.3 | (L1) Ensure 'Disallow Digest authentication' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Remote Management](<../GP Reports/Windows Remote Management.htm>) |
| **18.10.89.2** | **WinRM Service** | | |
| 18.10.89.2.1 | (L1) Ensure 'Allow Basic authentication' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Remote Management](<../GP Reports/Windows Remote Management.htm>) |
| 18.10.89.2.2 | (L2) Ensure 'Allow remote server management through WinRM' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Remote Management](<../GP Reports/Windows Remote Management.htm>) |
| 18.10.89.2.3 | (L1) Ensure 'Allow unencrypted traffic' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows Remote Management](<../GP Reports/Windows Remote Management.htm>) |
| 18.10.89.2.4 | (L1) Ensure 'Disallow WinRM from storing RunAs credentials' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows Remote Management](<../GP Reports/Windows Remote Management.htm>) |
| **18.10.90** | **Windows Remote Shell** | | |
| 18.10.90.1 | (L2) Ensure 'Allow Remote Shell Access' is set to 'Disabled' (Automated) | :white_large_square: | |
| **18.10.91** | **Windows Sandbox** | | |
| 18.10.91.1 | (L1) Ensure 'Allow clipboard sharing with Windows Sandbox' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| 18.10.91.2 | (L1) Ensure 'Allow networking in Windows Sandbox' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - Computer](<../GP Reports/Windows 11 - Computer.htm>) |
| **18.10.92** | **Windows Security (formerly Windows Defender Security Center)** | | |
| **18.10.92.1** | **Account protection** | | |
| **18.10.92.2** | **App and browser protection** | | |
| 18.10.92.2.1 | (L1) Ensure 'Prevent users from modifying settings' is set to 'Enabled' (Automated) | :white_large_square: | |
| **18.10.93** | **Windows Update** | | |
| **18.10.93.1** | **Legacy Policies** | | |
| 18.10.93.1.1 | (L1) Ensure 'No auto-restart with logged on users for scheduled automatic updates installations' is set to 'Disabled' (Automated) | :white_large_square: | |
| **18.10.93.2** | **Manage end user experience** | | |
| 18.10.93.2.1 | (L1) Ensure 'Configure Automatic Updates' is set to 'Enabled' (Automated) | :white_large_square: | |
| 18.10.93.2.2 | (L1) Ensure 'Configure Automatic Updates: Scheduled install day' is set to '0 - Every day' (Automated) | :white_large_square: | |
| 18.10.93.2.3 | (L1) Ensure 'Remove access to “Pause updates” feature' is set to 'Enabled' (Automated) | :white_large_square: | |
| **18.10.93.3** | **Manage updates offered from Windows Server Update Service** | | |
| **18.10.93.4** | **Manage updates offered from Windows Update (formerly Defer Windows Updates and Windows Update for Business)** | | |
| 18.10.93.4.1 | (L1) Ensure 'Manage preview builds' is set to 'Disabled' (Automated) | :white_large_square: | |
| 18.10.93.4.2 | (L1) Ensure 'Select when Preview Builds and Feature Updates are received' is set to 'Enabled: 180 or more days' (Automated) | :white_large_square: | |
| 18.10.93.4.3 | (L1) Ensure 'Select when Quality Updates are received' is set to 'Enabled: 0 days' (Automated) | :white_large_square: | |
| **19** | **Administrative Templates (User)** | | |
| **19.1** | **Control Panel** | | |
| **19.1.1** | **Add or Remove Programs** | | |
| **19.1.2** | **Display** | | |
| **19.1.3** | **Personalization (formerly Desktop Themes)** | | |
| 19.1.3.1 | (L1) Ensure 'Enable screen saver' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - User](<../GP Reports/Windows 11 - User.htm>) |
| 19.1.3.2 | (L1) Ensure 'Password protect the screen saver' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - User](<../GP Reports/Windows 11 - User.htm>) |
| 19.1.3.3 | (L1) Ensure 'Screen saver timeout' is set to 'Enabled: 900 seconds or fewer, but not 0' (Automated) | :ballot_box_with_check: | [Windows 11 - User](<../GP Reports/Windows 11 - User.htm>) |
| **19.2** | **Desktop** | | |
| **19.3** | **Network** | | |
| **19.4** | **Shared Folders** | | |
| **19.5** | **Start Menu and Taskbar** | | |
| **19.5.1** | **Notifications** | | |
| 19.5.1.1 | (L1) Ensure 'Turn off toast notifications on the lock screen' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - User](<../GP Reports/Diagnostics and Reporting - User.htm>) |
| **19.6** | **System** | | |
| **19.6.1** | **Ctrl+Alt+Del Options** | | |
| **19.6.2** | **Display** | | |
| **19.6.3** | **Driver Installation** | | |
| **19.6.4** | **Folder Redirection** | | |
| **19.6.5** | **Group Policy** | | |
| **19.6.6** | **Internet Communication Management** | | |
| **19.6.6.1** | **Internet Communication settings** | | |
| 19.6.6.1.1 | (L2) Ensure 'Turn off Help Experience Improvement Program' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - User](<../GP Reports/Diagnostics and Reporting - User.htm>) |
| **19.7** | **Windows Components** | | |
| **19.7.1** | **Add features to Windows 8 / 8.1 / 10 (formerly Windows Anytime Upgrade)** | | |
| **19.7.2** | **App runtime** | | |
| **19.7.3** | **Application Compatibility** | | |
| **19.7.4** | **Attachment Manager** | | |
| 19.7.4.1 | (L1) Ensure 'Do not preserve zone information in file attachments' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - User](<../GP Reports/Windows 11 - User.htm>) |
| 19.7.4.2 | (L1) Ensure 'Notify antivirus programs when opening attachments' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - User](<../GP Reports/Windows 11 - User.htm>) |
| **19.7.5** | **AutoPlay Policies** | | |
| **19.7.6** | **Calculator** | | |
| **19.7.7** | **Cloud Content** | | |
| 19.7.7.1 | (L1) Ensure 'Configure Windows spotlight on lock screen' is set to Disabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - User](<../GP Reports/Diagnostics and Reporting - User.htm>) |
| 19.7.7.2 | (L1) Ensure 'Do not suggest third-party content in Windows spotlight' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - User](<../GP Reports/Diagnostics and Reporting - User.htm>) |
| 19.7.7.3 | (L2) Ensure 'Do not use diagnostic data for tailored experiences' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - User](<../GP Reports/Diagnostics and Reporting - User.htm>) |
| 19.7.7.4 | (L2) Ensure 'Turn off all Windows spotlight features' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - User](<../GP Reports/Diagnostics and Reporting - User.htm>) |
| 19.7.7.5 | (L1) Ensure 'Turn off Spotlight collection on Desktop' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - User](<../GP Reports/Diagnostics and Reporting - User.htm>) |
| **19.7.8** | **Credential User Interface** | | |
| **19.7.9** | **Data Collection and Preview Builds** | | |
| **19.7.10** | **Desktop Gadgets** | | |
| **19.7.11** | **Desktop Window Manager** | | |
| **19.7.12** | **Digital Locker** | | |
| **19.7.13** | **Edge UI** | | |
| **19.7.14** | **File Explorer (formerly Windows Explorer)** | | |
| **19.7.15** | **File Revocation** | | |
| **19.7.16** | **IME** | | |
| **19.7.17** | **Instant Search** | | |
| **19.7.18** | **Internet Explorer** | | |
| **19.7.19** | **Location and Sensors** | | |
| **19.7.20** | **Microsoft Edge** | | |
| **19.7.21** | **Microsoft Management Console** | | |
| **19.7.22** | **Microsoft User Experience Virtualization** | | |
| **19.7.23** | **Multitasking** | | |
| **19.7.24** | **NetMeeting** | | |
| **19.7.25** | **Network Sharing** | | |
| 19.7.25.1 | (L1) Ensure 'Prevent users from sharing files within their profile.' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Diagnostics and Reporting - User](<../GP Reports/Diagnostics and Reporting - User.htm>) |
| **19.7.26** | **OOBE** | | |
| **19.7.27** | **Presentation Settings** | | |
| **19.7.28** | **Remote Desktop Services (formerly Terminal Services)** | | |
| **19.7.29** | **RSS Feeds** | | |
| **19.7.30** | **Search** | | |
| **19.7.31** | **Sound Recorder** | | |
| **19.7.32** | **Store** | | |
| **19.7.33** | **Tablet PC** | | |
| **19.7.34** | **Task Scheduler** | | |
| **19.7.35** | **Windows Calendar** | | |
| **19.7.36** | **Windows Color System** | | |
| **19.7.37** | **Windows Defender SmartScreen** | | |
| **19.7.38** | **Windows Error Reporting** | | |
| **19.7.39** | **Windows Hello for Business (formerly Microsoft Passport for Work)** | | |
| **19.7.40** | **Windows Installer** | | |
| 19.7.40.1 | (L1) Ensure 'Always install with elevated privileges' is set to 'Disabled' (Automated) | :ballot_box_with_check: | [Windows 11 - User](<../GP Reports/Windows 11 - User.htm>) |
| **19.7.41** | **Windows Logon Options** | | |
| **19.7.42** | **Windows Media Player** | | |
| **19.7.42.1** | **Networking** | | |
| **19.7.42.2** | **Playback** | | |
| 19.7.42.2.1 | (L2) Ensure 'Prevent Codec Download' is set to 'Enabled' (Automated) | :ballot_box_with_check: | [Windows 11 - User](<../GP Reports/Windows 11 - User.htm>) |
