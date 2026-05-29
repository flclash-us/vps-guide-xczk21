[English] Continuously updated ads/tracking/malware domain rules for AdGuard/Clash/dnsmasq/Pi-hole.

## Usage in Clash

rules:
  - RULE-SET,https://raw.githubusercontent.com/flclash-us/adblock-rules-z7klhz/main/rules/ad-domain.yaml,REJECT
  - GEOIP,CN,DIRECT
  - MATCH,DIRECT

Recommended Tools

- [Clash for Windows](https://clashforwindows.site/) - Most popular Clash GUI for Windows
- [ClashMI](https://clashmi.site/) - Lightweight multi-platform Clash client
- [FlClash](https://flclash.us/) - Modern proxy tool with multi-protocol support