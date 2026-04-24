# [Fork of 1Hosts](https://github.com/badmojr/1Hosts), in beta

***Safeguard your device(s) against pesky ads, trackers, and malware.***<br>

<p align="center">
    <a href="#"><img src="https://badgen.net/github/last-commit/badmojr/1Hosts?label=Updated&cache=0&color=purple&icon=github" alt="Last commit activity"></a>
    <a href="#"><img src="https://img.shields.io/github/repo-size/badmojr/1Hosts?logo=adblock&style=plastic" alt="Repo size"></a>
</p>

<br>
<p>
   1Hosts offers 2 blocklist variants tailored to different user needs:<br>
</p>

<h3 align="center"><id="Lite">🟢 <strong><ins>1Hosts (Lite)</ins></strong></h3>
<i>Balanced version - set & forget, prioritizes smooth UX, ideal for general users.</i>

<table align="center">
<thead>
<tr>
<th>Client</th>
<th>mirror 1</th>
<th>mirror 2</th>
<th>mirror 3</th>
</tr>
</thead>
<tbody>
<tr>
<td>AdAway</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/hosts.txt">view</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/hosts.txt">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/hosts.txt">view</a></td>
</tr>
<tr>
<td>Pi-hole / OpenSnitch</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/domains.txt">view</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/domains.txt">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/domains.txt">view</a></td>
</tr>
<tr>
<td>dnscrypt-proxy / personalDNSfilter / InviZible Pro</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/domains.wildcards">dl</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/domains.wildcards">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/domains.wildcards">dl</a></td>
</tr>
<tr>
<td>uBlock Origin / AdGuardHome</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/adblock.txt">view</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/adblock.txt">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/adblock.txt">view</a></td>
</tr>
<tr>
<td>DNSCloak</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/wildcards.txt">view</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/wildcards.txt">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/wildcards.txt">view</a></td>
</tr>
<tr>
<td>dnsmasq</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/dnsmasq.conf">dl</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/dnsmasq.conf">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/dnsmasq.conf">view</a></td>
</tr>
<tr>
<td>Knot / Bind9 / PowerDNS</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/rpz.txt">view</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/rpz.txt">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/rpz.txt">view</a></td>
</tr>
<tr>
<td>Unbound</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/unbound.conf">dl</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/unbound.conf">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/unbound.conf">view</a></td>
</tr>
<tr>
<td>Windows</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/hosts.win">dl</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/hosts.win">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/hosts.win">dl</a></td>
</tr>
<tr>
<td>Little Snitch</td>
<td><a href="https://badmojr.github.io/1Hosts/Lite/snitch.rules">dl</a></td>
<td><a href="https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/snitch.rules">view</a></td>
<td><a href="https://cdn.jsdelivr.net/gh/badmojr/1Hosts@master/Lite/snitch.rules">dl</a></td>
</tr>
</tbody>
</table>
<br>


<h3 align="center"><id="Xtra">🔴 <strong><ins>1Hosts (Xtra)</ins> <sup>Beta</sup></strong></h3>
    <i>Aggressive version - maximum blocking against emerging privacy threats. May (occasionally) disrupt legit sites or services.
</i>
<br><br>
    Available in all formats at <a href="https://github.com/badmojr/1Hosts/releases">releases</a>.

<br>
<br>

**Usage Notes**<br>
----------------

Choose between **Lite** and **Xtra** based on your needs, protection level, and tolerance for issues like false positives.

- **Lite**  
  For general users, beginners, families, or casual browsing where stability matters.  
  **Low false positives**: Accurate, non-disruptive blocking.

- **Xtra**  
  Ideal for *advanced users or privacy enthusiasts* focused on maximum threat mitigation, even if it requires troubleshooting.  
  However, it carries a **higher false positive rate**. This is an inherent trade-off for its aggressive nature, and users can report issues for removals. Not for everyone!

One easy trick is to use the "Lite" blocklist as your foundation, applied directly through a hosts file on your device.

This approach minimizes clutter in your DNS logs by handling basic blocking at the local level.
Given that the Lite list is exceptionally accurate and reliable, it allows you to swiftly pinpoint any issues—since queries blocked via the hosts file are stopped before they ever hit your DNS resolver (e.g., NextDNS with Xtra enabled).

<br>
Add the appropriate URL to your adblock client's settings or use DNS options below.<br>

<a href="https://controld.com/"><strong><em>ControlD: </em></strong></a>
updates every 30 minutes; supports subdomain/wildcard & CNAME blocking; unlimited queries.<br>
<table>
<thead>
<tr>
<th>Name</th>
<th>IPv4</th>
<th>IPv6</th>
<th>DNS-over-HTTPS</th>
<th>DNS-over-TLS</th>
</tr>
</thead>
<tbody>
<tr>
<td>1Hosts (Lite)</td>
<td>76.76.2.38 76.76.10.38</td>
<td>2606:1a40::38 2606:1a40:1::38</td>
<td><a href="https://freedns.controld.com/x-1hosts-lite">https://freedns.controld.com/x-1hosts-lite</a></td>
<td>x-1hosts-lite.freedns.controld.com</td>
</tr>
</tbody>
</table>
<br>

<strong><em>nextDNS: </em></strong>
updates every 30 minutes; customizable; supports subdomain/wildcard & CNAME blocking; capped at 300k queries per month (free); sign up required.<br>
Click <a href="https://nextdns.io/?from=jdduxcbq">here</a>.

<br>

<strong><em>AdGuard DNS: </em></strong>
updates every hour; customizable; supports subdomain/wildcard & CNAME blocking; 30-day (unlimited) trial available, then capped at 300k queries per month (free); sign up required.<br>
Click <a href="https://adguard-dns.io?aid=136327">here</a>.

<br>

<a href="https://rethinkdns.com"><strong><em>RethinkDNS: </em></strong></a>
updates infrequently; supports subdomain/wildcard & CNAME blocking; unlimited queries; open-source.<br>
<table>
<thead>
<tr>
<th>Name</th>
<th>DNS-over-HTTPS</th>
<th>DNS-over-TLS</th>
</tr>
</thead>
<tbody>
<tr>
<td>1Hosts (Lite)</td>
<td><a href="https://max.rethinkdns.com/1:AAQCAA==">https://max.rethinkdns.com/1:AAQCAA==</a></td>
<td>1-aacaeaa.max.rethinkdns.com</td>
</tr>
</tbody>
</table>
<br><br>

 **Compatible Software Suite**<br>
- **Android**: [AdAway](https://adaway.org/), [Blokada](https://blokada.org/), [personalDNSfilter](https://www.zenz-solutions.de/personaldnsfilter-wp/), [RethinkDNS](https://rethinkfirewall.com/), [InviZible Pro](https://invizible.net/en/)
- **iOS**: [DNSCloak](https://apps.apple.com/us/app/dnscloak-secure-dns-client/id1452162351)
- **PC**: [uBlock Origin](https://github.com/gorhill/uBlock#installation), [AdGuardHome](https://adguard.com/en/adguard-home-overview.html?aid=31921), [dnscrypt-proxy](https://www.dnscrypt.org/)
- **Others**: [Pi-hole](https://pi-hole.net/), [OpenSnitch](https://github.com/evilsocket/opensnitch/wiki), [Knot](https://knot-resolver.cz/), [Bind9](https://www.isc.org/bind/), [PowerDNS](https://www.powerdns.com/recursor.html), [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html), [Unbound](https://nlnetlabs.nl/projects/unbound/about/), [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html)

<br>

**Why 1Hosts?**<br>
----------------

Highly effective, compact, and actively maintained (since: Dec 2, 2017).
Smaller in size compared to alternatives, yet blocks more for many users.

⠀
----------------
<p align="center"><strong>Credits & ©:</strong> <br>
  <a href="./-data/lists/assets.txt">To the curators whose diligence underpins this endeavor, thank you!</a> <br></p><br>

<p align="center"><strong>mentions</strong> <br>
<a href="https://github.com/yokoffing/NextDNS-Config">Config NextDNS</a><br>
<a href="https://controld.com/free-dns?freeResolverType=x-1hosts-lite&helpPane=platform">ControlD Setup</a> <br>
<a href="https://grokipedia.com/page/1Hosts">Wiki</a> <br>
</p>

<br>

_Help us create a better experience <3!_  
- ⭐ Star the repo.
- Report false positives or issues via [GitHub Issues](https://github.com/badmojr/1Hosts/issues).
- Share with friends for a safer web.

<a href="https://youtube.com/@MarvelousQuran"><img src="./-data/static/img/mq.jpg" title="Watch MarvelousQuran's amazing videos">
