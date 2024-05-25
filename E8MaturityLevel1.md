---
name: Essential 8 - Maturity Level One
...

#### Patch applications
* An automated method of asset discovery is used at least fortnightly to support the detection of assets for subsequent vulnerability scanning activities.
* A vulnerability scanner with an up-to-date vulnerability database is used for vulnerability scanning activities.
* A vulnerability scanner is used at least daily to identify missing patches or updates for vulnerabilities in online services.
* A vulnerability scanner is used at least weekly to identify missing patches or updates for vulnerabilities in office productivity suites, web browsers and their extensions, email clients, PDF software, and security products.
* Patches, updates or other vendor mitigations for vulnerabilities in online services are applied within 48 hours of release when vulnerabilities are assessed as critical by vendors or when working exploits exist. 
* Patches, updates or other vendor mitigations for vulnerabilities in online services are applied within two weeks of release when vulnerabilities are assessed as non-critical by vendors and no working exploits exist. 
* Patches, updates or other vendor mitigations for vulnerabilities in office productivity suites, web browsers and their extensions, email clients, PDF software, and security products are applied within two weeks of release. 
* Online services that are no longer supported by vendors are removed. 
* Office productivity suites, web browsers and their extensions, email clients, PDF software, Adobe Flash Player, and security products that are no longer supported by vendors are removed.

#### Patch operating systems
* An automated method of asset discovery is used at least fortnightly to support the detection of assets for subsequent vulnerability scanning activities.
* A vulnerability scanner with an up-to-date vulnerability database is used for vulnerability scanning activities.
* A vulnerability scanner is used at least daily to identify missing patches or updates for vulnerabilities in operating systems of * internet-facing servers and internet-facing network devices.
* A vulnerability scanner is used at least fortnightly to identify missing patches or updates for vulnerabilities in operating systems of workstations, non-internet-facing servers and non-internet-facing network devices.
* Patches, updates or other vendor mitigations for vulnerabilities in operating systems of internet-facing servers and internet-facing network devices are applied within 48 hours of release when vulnerabilities are assessed as critical by vendors or when working exploits exist.
* Patches, updates or other vendor mitigations for vulnerabilities in operating systems of internet-facing servers and internet-facing network devices are applied within two weeks of release when vulnerabilities are assessed as non-critical by vendors and no working exploits exist.
* Patches, updates or other vendor mitigations for vulnerabilities in operating systems of workstations, non-internet-facing servers and non-internet-facing network devices are applied within one month of release.
* Operating systems that are no longer supported by vendors are replaced.

#### Multi-factor authentication
* Multi-factor authentication is used to authenticate users to their organisation’s online services that process, store or communicate their organisation’s sensitive data.
* Multi-factor authentication is used to authenticate users to third-party online services that process, store or communicate their organisation’s sensitive data.
* Multi-factor authentication (where available) is used to authenticate users to third-party online services that process, store or communicate their organisation’s non-sensitive data.
* Multi-factor authentication is used to authenticate users to their organisation’s online customer services that process, store or communicate their organisation’s sensitive customer data.
* Multi-factor authentication is used to authenticate users to third-party online customer services that process, store or communicate their organisation’s sensitive customer data.
* Multi-factor authentication is used to authenticate customers to online customer services that process, store or communicate sensitive customer data.
* Multi-factor authentication uses either: something users have and something users know, or something users have that is unlocked by something users know or are.

#### Restrict administrative privileges
* Requests for privileged access to systems, applications and data repositories are validated when first requested.
* Privileged users are assigned a dedicated privileged account to be used solely for duties requiring privileged access.
* Privileged accounts (excluding those explicitly authorised to access online services) are prevented from accessing the internet, email and web services.
* Privileged accounts explicitly authorised to access online services are strictly limited to only what is required for users and services to undertake their duties.
* Privileged users use separate privileged and unprivileged operating environments.
* Unprivileged accounts cannot logon to privileged operating environments.
* Privileged accounts (excluding local administrator accounts) cannot logon to unprivileged operating environments.

#### Application control
* Application control is implemented on workstations.
* Application control is applied to user profiles and temporary folders used by operating systems, web browsers and email clients.
* Application control restricts the execution of executables, software libraries, scripts, installers, compiled HTML, HTML applications and control panel applets to an organisation-approved set.

#### Restrict Microsoft Office macros
* Microsoft Office macros are disabled for users that do not have a demonstrated business requirement.
* Microsoft Office macros in files originating from the internet are blocked.
* Microsoft Office macro antivirus scanning is enabled.
* Microsoft Office macro security settings cannot be changed by users.

#### User application hardening
* Internet Explorer 11 is disabled or removed.
* Web browsers do not process Java from the internet.
* Web browsers do not process web advertisements from the internet.
* Web browser security settings cannot be changed by users.

#### Regular backups
* Backups of data, applications and settings are performed and retained in accordance with business criticality and business continuity requirements.
* Backups of data, applications and settings are synchronised to enable restoration to a common point in time.
* Backups of data, applications and settings are retained in a secure and resilient manner.
* Restoration of data, applications and settings from backups to a common point in time is tested as part of disaster recovery exercises.
* Unprivileged accounts cannot access backups belonging to other accounts.
* Unprivileged accounts are prevented from modifying and deleting backups.