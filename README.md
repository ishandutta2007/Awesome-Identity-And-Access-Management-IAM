# Awesome-Identity-And-Access-Management-IAM

# Top Identity and Access Management (IAM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Authentication, Authorization & Self-Hosted Identity Platforms*  
**Last updated: October 2026**

This repository tracks notable **commercial IAM platforms** and **open-source projects** that manage digital identities, enforce access policies, and secure authentication across enterprise and customer-facing applications — from SSO and MFA to privileged access management and identity governance.

**Examples** include AWS IAM, Okta, Microsoft Entra ID, Ping Identity, CyberArk, JumpCloud, OneLogin, SailPoint, BeyondTrust, and ForgeRock (the category leaders).

**Open-source emphasis**: Identity and access management is one of the strongest open-source domains. **Keycloak** leads with 36,000+ GitHub stars as the de facto open-source IAM platform . **Authentik** brings flexible flow-based authentication with 10,000+ stars . **Zitadel** delivers multi-tenant native identity infrastructure . **Ory** provides a modular identity stack (Kratos, Hydra, Keto, Oathkeeper) . **Casdoor** offers a UI-first IAM platform with 10,000+ stars . **WSO2 Identity Server** and **Apache Syncope** handle enterprise IGA . **MaxKey**, **Janssen**, and **Gluu** round out the ecosystem . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Okta](https://www.okta.com/)**  
  **The market-leading independent IAM platform** — SSO, MFA, lifecycle management, and API access management . **The most widely integrated workforce identity platform** . **Best for enterprise identity**.

- **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**  
  **Microsoft's cloud identity platform** — SSO, conditional access, MFA, and 10,000+ SaaS app integrations . **Free tier with Microsoft 365**; Premium P1/P2 for advanced features . **Best for Microsoft-centric organizations** .

- **[AWS IAM](https://aws.amazon.com/iam/)**  
  **AWS's identity and access management** — fine-grained access control for AWS resources . **IAM Identity Center** for workforce SSO across AWS accounts . **Best for AWS-native identity** .

- **[Ping Identity](https://www.pingidentity.com/)**  
  **Enterprise identity platform** — SSO, MFA, and identity governance . **Best for large enterprises** .

- **[CyberArk](https://www.cyberark.com/)**  
  **Privileged access management leader** — secure privileged accounts, credentials, and sessions . **Best for privileged access management** .

- **[JumpCloud](https://jumpcloud.com/)**  
  **The cloud directory platform** — unified directory, SSO, device management, and LDAP . **Free for up to 10 users** . **Best for SMBs wanting cloud directory** .

- **[OneLogin](https://www.onelogin.com/)**  
  **Workforce identity** — directory, SSO, and MFA . **Best for mid-market enterprises** .

- **[SailPoint](https://www.sailpoint.com/)**  
  **Identity governance and administration leader** — access certifications, role management, and compliance . **Best for enterprise IGA** .

- **[BeyondTrust](https://www.beyondtrust.com/)**  
  **Privileged access management** — secure remote access and privilege management . **Best for PAM** .

- **[ForgeRock](https://www.forgerock.com/)**  
  **Enterprise identity platform** — CIAM and workforce identity . **Best for large-scale consumer identity** .

## Open-Source GitHub Projects

### Full-Featured IAM Platforms

- **[Keycloak](https://github.com/keycloak/keycloak)**  
  **The leading open-source identity and access management solution**, Apache-2.0 licensed with **36,000+ GitHub stars** . **SSO, MFA, identity brokering, user federation, and fine-grained authorization** . **OAuth 2.0, OIDC, and SAML 2.0 support** . **Multi-tenancy via realms** — each realm is an isolated tenant . **The de facto open-source IAM platform** — used by enterprises, governments, and SaaS providers worldwide . **Best for comprehensive IAM**.

- **[Authentik](https://github.com/goauthentik/authentik)**  
  **Flexible open-source identity provider**, MIT/GPL licensed with **10,000+ GitHub stars** . **OAuth2, SAML, LDAP, and proxy support** . **Flow-based authentication customization** — visual editor for login flows . **Best for IAM with customization flexibility** .

- **[Zitadel](https://github.com/zitadel/zitadel)**  
  **Identity infrastructure with native multi-tenancy**, Apache-2.0 licensed . **OIDC, OAuth2, SAML2, passkeys/FIDO2, and SCIM 2.0** . **Organizations and projects** provide built-in tenant isolation . **API-first with modern architecture** . **Best for multi-tenant SaaS IAM** .

- **[Ory](https://github.com/ory)**  
  **Open-source identity infrastructure** — Kratos (identity management), Hydra (OAuth2), Keto (authorization), and Oathkeeper (access proxy) . Apache-2.0 licensed . **API-first, cloud-native design** . **The most modular open-source identity stack** . **Best for developers building custom IAM** .

- **[Casdoor](https://github.com/casdoor/casdoor)**  
  **UI-first identity and access management platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **OAuth2, OIDC, SAML, LDAP, and CAS support** . **Built-in admin console and extensive SDKs** . **Best for UI-driven IAM** .

### Enterprise IGA & Federation

- **[WSO2 Identity Server](https://github.com/wso2/product-is)**  
  **Enterprise-grade open-source IAM**, Apache-2.0 licensed . **SSO, MFA, adaptive authentication, and identity governance** . **The most enterprise-focused open-source IAM** . **Best for large enterprises** .

- **[Apache Syncope](https://github.com/apache/syncope)**  
  **Open-source identity governance and administration (IGA)**, Apache-2.0 licensed . **User provisioning, de-provisioning, and access certification** . **Workflow engine with BPMN 2.0 support** . **Scales to a million entities** . **Best for identity governance with workflow automation** .

- **[MaxKey](https://github.com/dromara/MaxKey)**  
  **Leading IAM/IDaaS product**, Apache-2.0 licensed . **OAuth2.x, OpenID Connect, SAML2.0, JWT, CAS, and SCIM support** . **RBAC-based unified permission control** with full user lifecycle management . **Best for enterprise IAM with broad protocol support** .

- **[Janssen Project](https://github.com/JanssenProject/jans)**  
  **Cloud-native IAM platform under Linux Foundation**, Apache-2.0 licensed . **Auth Server (OAuth/OpenID), Agama low-code identity orchestration, and Cedarling policy decision point** . **Best for cloud-native IAM** .

- **[Gluu](https://github.com/GluuFederation)**  
  **Open-source IAM platform**, Apache-2.0 licensed . **SSO, MFA, and identity federation** . **Best for comprehensive IAM suite** .

### Authorization & Policy

- **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)**  
  **General-purpose policy engine**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Unified policy enforcement across cloud, Kubernetes, and CI/CD** . **Best for policy-as-code authorization** .

- **[OpenFGA](https://github.com/openfga/openfga)**  
  **Fine-grained authorization**, Apache-2.0 licensed . **Google Zanzibar-inspired relationship-based access control** . **Best for fine-grained authorization** .

- **[SpiceDB](https://github.com/authzed/spicedb)**  
  **Authorization database**, Apache-2.0 licensed . **Zanzibar-inspired permissions system** . **Best for relationship-based authorization** .

- **[Casbin](https://github.com/casbin/casbin)**  
  **Open-source authorization library**, Apache-2.0 licensed with **17,000+ GitHub stars** . **ACL, RBAC, and ABAC** . **Best for application-level authorization** .

- **[Permify](https://github.com/Permify/permify)**  
  **Open-source authorization service**, Apache-2.0 licensed . **Zanzibar-inspired with multi-tenancy** . **Best for authorization service** .

- **[Cerbos](https://github.com/cerbos/cerbos)**  
  **Policy-as-code authorization**, Apache-2.0 licensed . **Language-agnostic with stateless design** . **Best for policy-based authorization** .

### Additional Strong Open-Source Options

- **Authelia** — Authentication and authorization server with 2FA and forward-auth for reverse proxies .
- **Dex** — Open-source OIDC identity provider, CNCF sandbox project for Kubernetes .
- **Pomerium** — Identity-aware access proxy with SSO integration for BeyondCorp-style access .
- **Kanidm** — Modern identity management platform in Rust with passkeys and SSH key distribution .
- **FusionAuth** — Open-source identity and access management with SSO, MFA, and user management .
- **Bouncer** — Open-source SSO platform (formerly SuperTokens) .
- **LLDAP** — Lightweight LDAP server for self-hosted identity .
- **FreeIPA** — Identity management for Linux/Unix environments .
- **Samba AD** — Active Directory compatible domain controller .
- **OpenDJ** — LDAPv3-compliant directory service with REST/JSON access .
- **Apache Directory** — LDAP server and directory tools .

**Frameworks for building custom IAM solutions**: Combine **Keycloak** for comprehensive IAM with SSO, MFA, and federation . Use **Authentik** or **Zitadel** for flexible, modern identity platforms . Deploy **Ory** for modular, API-first identity infrastructure . Choose **Casdoor** for UI-driven IAM . Integrate **WSO2 Identity Server** or **Apache Syncope** for enterprise IGA . Use **Open Policy Agent**, **OpenFGA**, or **SpiceDB** for fine-grained authorization . Choose **Authelia** or **Pomerium** for identity-aware access proxy . Note that true enterprise IAM with managed infrastructure, global scaling, and vendor-supported SLAs (Okta, Entra ID, Ping Identity) remains primarily commercial territory; open-source stacks provide strong identity, authorization, and governance foundations that require integration for complete IAM deployments.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- IAM platforms handle sensitive authentication data and access controls. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA, SOC 2).
- **Identity is the new security perimeter** — a compromised IAM grants access to everything. Harden deployments with MFA, rate limiting, and monitoring .
- **License considerations**: Keycloak uses Apache-2.0, Authentik uses MIT/GPL, Zitadel uses Apache-2.0, Ory uses Apache-2.0, and Casdoor uses Apache-2.0. Verify licensing against your use case before committing.
- The open-source ecosystem provides strong identity, authorization, and governance foundations, but **managed infrastructure, global scale, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for identity architects, security engineers, and organizations seeking IAM sovereignty.**
Let's make identity and access management more open, transparent, and secure.
