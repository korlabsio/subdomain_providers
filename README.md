# subdomain_providers
A curated list of free subdomain providers and dynamic DNS providers with their type

### Description

This list provides active domain names that provide services to users like free hosting services (in terms of subdomains) or dynamic DNS providers as subdomain. The goal is to be able to detect a domain name as either user-registered domain or service provider.

The distinction is important since the take-down/mitigation action is different and can be performed by different entities.

For example, a domain name registered by an attacker to spread malware can be taken down by the registrar/registry. However, registries/registrars can not take down Google Drive free service in case of malware spread. Instead, one can notify Google for this case.

The list is provided in the [names](./names) files in this repository. It's a two-column CSV file as follows:

1. first column: registered domain name
2. Second column: Type of service provider

#### Type of service provider

Type of service provider (second column) is one of the following:

1. fsp: Free Subdomain Provider
2. psp: Paid Subdomain Provider
3. ddns: Dynamic DNS Provider
4. fss: File Sharing Service
5. csp: Cloud Service Provider
6. fpp: Free Page Provider
7. tss: Text Sharing Service
8. lrs: Link redirection service
9. ipfs: InterPlanetary File System

Feel free to open an issue for updating the list!
