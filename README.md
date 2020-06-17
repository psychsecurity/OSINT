# OSINT
Cheatsheet for OSINT - check out https://osintframework.com for detailed framework

## DOMAINS

### WHOIS

`whois DOMAIN`

### robtex

`https://www.robtex.com/dns-lookup/domain.com`

### Domain analyser

`python domain_analyzer.py -d domain.com -w -j -n -a`

### RiskIQ

`https://community.riskiq.com`

### amass

`amass enum -v -src -ip -brute -min-for-recursive 2 -d domain.com`

### censys

`python3 censys_subdomain_finder.py domain.com`

### sublist3r

`python sublist3r.py -d domain.com`

### subfinder

`docker run -v $HOME/.config/subfinder:/root/.config/subfinder -it projectdiscovery/subfinder -d domain.com`



