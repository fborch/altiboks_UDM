# altiboks_UDM
Oppskrift på oppsett av altiboks mot Unifi Dream Machine Pro

Innledning

Altiboks distribuerer internett over VLAN 102. Vedlagt følger de viktigste innstillingene som må settes på UDM Pro. Skjermbilder tatt November 2023. Dette omhandler kun internett, ikke IPTV.

## Generelle nettverksinnstillinger:
![general_network](https://github.com/fborch/altiboks_UDM/assets/14937023/7cfe0a22-e038-49ff-9b6e-8879377f8650)

IPV6 forklaring: https://help.ui.com/hc/en-us/articles/115005868927-UniFi-Gateway-Static-IPv6-and-DHCPv6-Prefix-Delegation

## Innstillinger på ditt nettverk:
![specific network](https://github.com/fborch/altiboks_UDM/assets/14937023/7e0461eb-6d1f-4048-8226-9af1041a67df)

Anbefalte offentlige DNS-servere:

    Google: 8.8.8.8 & 8.8.4.4.
    Quad9: 9.9.9.9 & 149.112.112.112.
    OpenDNS: 208.67.222.222 & 208.67.220.220.
    Cloudflare: 1.1.1.1 & 1.0.0.1.
    CleanBrowsing: 185.228.168.9 & 185.228.169.9.
    Alternate DNS: 76.76.19.19 & 76.223.122.150.
    AdGuard DNS: 94.140.14.14 & 94.140.15.15.

Forklaring SLAAC: https://www.networkacademy.io/ccna/ipv6/stateless-address-autoconfiguration-slaac

## Internettinnstillinger:
![intern_settings](https://github.com/fborch/altiboks_UDM/assets/14937023/af7c9c47-62b1-45db-bfdd-75c72f51b103)

IPV6 forklaring: https://help.ui.com/hc/en-us/articles/115005868927-UniFi-Gateway-Static-IPv6-and-DHCPv6-Prefix-Delegation

Kilder:


* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/#comment-25607541

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/3/#comment-26013562

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/5/#comment-26509430

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/6/#comment-26622994

* https://www.altibox.no/privat/kundeservice/hjelp-til-internett/hjemmesentral/vmg-2/

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/7/#comment-26821629

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/7/#comment-26822606
