# Hackers' 🍺 Brew 
> *A Homebrew / Linuxbrew tap to install InfoSec and Hacking Tools and Utilities on Linux, BSD, and macOS.*

🎯 The **objective** of this tap is to simplify the distribution of **InfoSec / Hacking tools and utilities** on **a wide-range of Linux Distros** and **macOS**. 

**_There's also an intention to support BSD but currently, it is very experimental. Progress is dependant on Homebrew support with BSD._**

---
### 🤔 Wait, why Homebrew 🍻?
**Homebrew** 🍻 is one of the few **package 📦 managers**  that is aiming to **support multiple OSs (i.e.
macOS, Linux, WSL, BSD)**.

👉 Utilizing **Homebrew** 🍻 and **this tap**, we intend to **provide 🎁 users** with **OS agnostic solution to install, setup, and deploy their InfoSec / Hacking toolbelt** through the use of a single uniform tool 🔧.

## 💾 Install
```bash
brew tap open-arsenal/hackers-brew
```
🖐 *If it's not obvious*, you **must** have first installed 👉 [**Homebrew on macOS**](https://docs.brew.sh/Installation) **or** 👉 [**Linux**](https://docs.brew.sh/Homebrew-on-Linux). 

**👉 For BSD, [may try these instructions to install Homebrew; which are translated to English.](https://translate.google.com/translate?hl=en&sl=ja&u=https://qiita.com/cielavenir/items/741921fcecb281555f77&prev=search)** [[Original Link in Japanese](https://qiita.com/cielavenir/items/741921fcecb281555f77)]

### 🛡 Prepare Your System
If you haven't taken any steps in securing your OS, we recommend you take a look at the following guides and do whatever you deem necessary:

- 💪 **macOS**: [@drduh's](https://github.com/drduh) [masOS Security and Privacy Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
- 💪 **Linux (Debian)**: [@drduh's](https://github.com/drduh) [Debian Security and Privacy Guide](https://github.com/drduh/Debian-Privacy-Server-Guide)

## 🤷‍♂️ Already on Homebrew?
There're already several useful binaries and applications available on **Homebrew's Offical Taps 👍**. _These you won't find 👀 in this repo. Any updates we have are usally already contributed to Homebrew 🍻._

👉 Below you'll find a list of tools spotted in **The Offical Homebrew Tap 👍**.


###Wi-Fi Hacking Tools
- `aircrack-ng` - `Next-generation aircrack with lots of new features`


###ARP Tools
- `arp-scan` - `ARP scanning and fingerprinting tool`
- `arp-sk` - `ARP traffic generation tool`
- `arping` - `Utility to check whether MAC addresses are already taken on a LAN`
- `arpoison` - `UNIX arp cache update utility`


###Shells
- `dsh` - `Dancer's shell, or distributed shell`
- `rssh` - `Restricted shell for use with OpenSSH`


###Analyzing Tools
- `fail2ban` - `Scan log files and ban IPs showing malicious signs`
- `http_load` - `Test throughput of a web server by running parallel fetches`
- `httpdiff` - `Compare two HTTP(S) responses`
- `httperf` - `Tool for measuring webserver performance`
- `httpflow` - `Packet capture and analysis utility similar to tcpdump for HTTP`
- `wireshark` - `Graphical network analyzer and capture tool`
- `httpry` - `Packet sniffer for displaying and logging HTTP traffic`
- `mergelog` - `Merges httpd logs from web servers behind round-robin DNS`
- `netpref` - `Benchmarks performance of many different types of networking`
- `masscan` - `TCP port scanner, scans entire Internet in under 5 minutes`
- `siege` - `HTTP regression testing and benchmarking utility`
- `speedtest-cli` - `Command-line interface for https://speedtest.net bandwidth tests`
- `shmcat` - `Tool that dumps shared memory segments (System V and POSIX)`
- `subnetcalc` - `IPv4/IPv6 subnet calculator`
- `synscan` - `Asynchronous half-open TCP portscanner`
- `tsung` - `Load testing for HTTP, PostgreSQL, Jabber, and others`
- `vegeta` - `HTTP load testing tool and library`
- `weighttp` - `Webserver benchmarking tool that supports multithreading`
- `slowhttptest` - `Simulates application layer denial of service attacks`
- `wiremock-standalone` - `Simulator for HTTP-based APIs`
- `wpscan` - `Black box WordPress vulnerability scanner`
- `wrk` - `HTTP benchmarking tool`


###HTTP Tools
- `apib` - `HTTP performance-testing tool`
- `curl` - `Get a file from an HTTP, HTTPS or FTP server`
- `curl-openssl` - `Get a file from an HTTP, HTTPS or FTP server`
- `fabio` - `Zero-conf load balancing HTTP(S) router`
- `fortio` - `HTTP and gRPC load testing and visualization tool and server`
- `gor` - `Real-time HTTP traffic replay tool written in Go`
- `haproxy` - `Reliable, high performance TCP/HTTP load balancer`
- `hey` - `HTTP load generator, ApacheBench (ab) replacement`
- `http-parser` - `HTTP request/response parser for c`
- `httpie` - `User-friendly cURL replacement (command-line HTTP client)`
- `httping` - `Ping-like tool for HTTP requests`
- `httptunnel` - `Tunnels a data stream in HTTP requests`
- `mitmproxy` - `Intercept, modify, replay, save HTTP/S traffic`
- `neon` - `HTTP and WebDAV client library with a C interface`
- `nghttp2` - `HTTP/2 C Library`
- `sproxy` - `HTTP proxy server collecting URLs in a 'siege-friendly' manner`
- `squid` - `Advanced proxy caching server for HTTP, HTTPS, FTP, and Gopher`
- `tinyproxy` - `HTTP/HTTPS proxy for POSIX systems`
- `trafficserver` - `HTTP/1.1 compliant caching proxy server`
- `varnish` - `High-performance HTTP accelerator`
- `whistle` - `HTTP, HTTP2, HTTPS, Websocket debugging proxy`


###SSH Tools
- `apt-dater` - `Manage package updates on remote hosts using SSH`
- `assh` - `Advanced SSH config - Regex, aliases, gateways, includes and dynamic hosts`
- `autossh` - `Automatically restart SSH sessions and tunnels`
- `connect` - `Provides SOCKS and HTTPS proxy support to SSH`
- `corkscrew` - `Tunnel SSH through HTTP proxies`
- `csshx` - `Cluster ssh tool for Terminal.app`
- `dropbear` - `Small SSH server/client for POSIX-based system`
- `duo_unix` - `Two-factor authentication for SSH`
- `fabric` - `Library and command-line tool for SSH`
- `git-ssh` - `Proxy for serving git repositories over SSH`
- `github-keygen` - `Bootstrap GitHub SSH configuration`
- `gssh` - `SSH automation tool based on Groovy DSL`
- `hss` - `Interactive parallel SSH client`
- `keepkey-agent` - `Keepkey Hardware-based SSH/GPG agent` (same as `trezor-agent`)
- `libssh` - `C library SSHv1/SSHv2 client and server protocols`
- `libssh2` - `C library implementing the SSH2 protocol`
- `monkeysphere` - `Use the OpenPGP web of trust to verify ssh connections`
- `mpssh` - `Mass parallel ssh`
- `putty` - `Implementation of Telnet and SSH`
- `rmate` - `Edit files from an SSH session in TextMate`
- `ssh-audit` - `SSH server & client auditing`
- `ssh-copy-id` - `Add a public key to a remote machine's authorized_keys file`
- `ssh-permit-a38` - `Central management and deployment for SSH keys`
- `ssh-vault` - `Encrypt/decrypt using SSH keys`
- `sshfs` - `File system client based on SSH File Transfer Protocol`
- `sshguard` - `Protect from brute force attacks against SSH`
- `sshrc` - `Bring your .bashrc, .vimrc, etc. with you when you SSH`
- `sshtrix` - `SSH login cracker`
- `stormssh` - `Command-line tool to manage your ssh connections`
- `stormssh-completion` - `Completion for storm-ssh`
- `teleport` - `Modern SSH server for teams managing distributed infrastructure`
- `trezor-agent` - `Hardware SSH/GPG agent for Trezor, Keepkey & Ledger` (same as `keepkey-agent`)
- `vassh` - `Vagrant Host-Guest SSH Command Wrapper/Proxy/Forwarder`
- `zssh` - `Interactive file transfers over SSH`


###Web Servers
- `algernon` - `Pure Go web server with Lua, Markdown, HTTP/2 and template support`
- `armour` - `Uncomplicated, modern HTTP server`
- `caddy` - `Alternative general-purpose HTTP/2 web server`
- `darkhttpd` - `Small static webserver without CGI`
- `h2o` - `HTTP server with support for HTTP/1.x and HTTP/2`
- `http-server` - `Simple zero-configuration command-line HTTP server`
- `httpd` - `Apache HTTP server`
- `libevhtp` - `Create extremely-fast and secure embedded HTTP servers with ease`
- `libhttpserver` - `C++ library of embedded Rest HTTP server`
- `libmicrohttpd` - `Light HTTP/1.1 server library`
- `lightpd` - `Small memory footprint, flexible web-server`
- `mighttpd2` - `HTTP server`
- `mockserver` - `Mock HTTP server and proxy`
- `nginx` - `HTTP(S) server and reverse proxy, and IMAP/POP3 proxy server`
- `serve` - `Static http server anywhere you need one`
- `wbox` - `HTTP testing tool and configuration-less HTTP server`
- `webfs` - `HTTP server for purely static content`


###To Organize
- `aws-keychain` - `Uses macOS keychain for storage of AWS credentials`
- `certbot` - `Tool to obtain certs from Let's Encrypt and autoenable HTTPS`
- `clam-av` - `Anti-virus software`
- `exploitdb` - `The official Exploit Database`
- `git-remote-gcrypt` - `GPG-encrypted git remotes`
- `gnunet` - `Framework for distributed, secure and privacy-preserving applications`
- `gpgme` - `Library access to GnuPG`
- `gnupg` - `GNU Pretty Good Privacy (PGP) package`
- `hopenpgp-tools` - `Command-line tools for OpenPGP-related operations`
- `ike-scan` - `Discover and fingerprint IKE hosts`
- `libgpg-error` - `Common error values for all GnuPG components`
- `libhttpseverywhere` - `Bring HTTPSEverywhere to desktop apps`
- `libyubikey` - `C library for manipulating Yubico one-time passwords`
- `net-snmp` - `Implements SNMP v1, v2c, and v3, using IPv4 and IPv6`
- `netcat` - `Utility for managing network connections`
- `netcat6` - `Rewrite of netcat that supports IPv6, plus other improvements`
- `netdata` - `Distributed real-time performance and health monitoring`
- `nethogs` - `Net top tool grouping bandwidth per process`
- `nettle` - `Low-level cryptographic library`
- `openldap` - `Open source suite of directory software`
- `openssl` - `Cryptography and SSL/TLS Toolkit`
- `pam_yubico` - `Yubico pluggable authentication module`
- `paperkey` - `Extract just secret information out of OpenPGP secret keys`
- `pgpdump` - `PGP packet visualizer`
- `pinentry-mac` - `Pinentry for GPG on Mac`
- `pius` - `PGP individual UID signer`
- `proxytunnel` - `Create TCP tunnels through HTTPS proxies`
- `qtkeychain` - `Platform-independent Qt API for storing passwords securely`
- `rinetd` - `Internet TCP redirection server`
- `scm-manager` - `Manage Git, Mercurial, and Subversion repos over HTTP`
- `telnet` - `User interface to the TELNET protocol (built from macOS Sierra sources)`
- `telnetd` - `TELNET server (built from macOS Sierra sources)`
- `twtxt` - `Decentralised, minimalist microblogging service for hackers`
- `udpxy` - `UDP-to-HTTP multicast traffic relay daemon`
- `urh` - `Universal Radio Hacker`
- `wirouter_keyrec` - `Recover the default WPA passphrases from supported routers`
- `ykclient` - `Library to validate YubiKey OTPs against YubiCloud`
- `ykman` - `Tool for managing your YubiKey configuration`
- `ykpers` - `YubiKey personalization library and tool`
- `yubico-piv-tool` - `Command-line tool for the YubiKey PIV application`


## Homebrew Cask
👉 There're some tools available on **The Offical Homebrew Cask Tap 👍** as well. These are available to `macOS` users only.

- `angry-ip-scanner` - `Angry IP Scanner`
- `avg-antivirus` - `AVG Antivirus for Mac`
- `f-secure-anti-virus` - `F-Secure Anti-Virus`
- `avira-antivirus` - `Avira Antivirus`
- `beacon-scanner` - `BeaconScanner`
- `gpg-suite-nightly` - `GPG Suite Nightly`
- `gpg-suite-pinentry`- `GPG Suite Pinentry`
- `gpg-suite`- `GPG Suite`
- `gpg-suite-no-mail`- `GPG Suite (without GPG Mail)`
- `gpg-sync`- `GPG Sync`
- `http-toolkit` - `HTTP Toolkit`
- `little-snitch` - `Little Snitch`
- `little-snitch-nightly` - `Little Snitch Nightly`
- `metasploit` - `Metasploit`
- `murus` - `Murus Firewall`
- `murus-menulet` - `Murus Firewall`
- `radio-silence` - `Raido Silence`
- `ssh-tunnel-manager` - `SSH Tunnel Manager`
- `wireshark` - `Wireshark`
- `wireshark-chmodbpf` - `The ChmodBPF package from the current Wireshark stable install package.`

## 💀 Graveyard
It's true **"nothing lasts forever."** These tools 🛠 have run their course and for whatever reason, are stopped being mantained and supported. 😵

## ✋ Requests
**Requests will be automatically closed.** If you want something added, 🙏 **submit a pull request**.

___
---
###### 🚨 DISCLAIMER: PLEASE NOTE 📝 EVERYTHING STORED IN THIS REPO IS AVAILABLE EXCLUSIVELY FOR ACADEMIC AND RESEARCH PURPOSES. THE MAINTAINERS AND CONTRIBUTORS DO NOT CONDONE THEIR USE IN ANY ILLEGAL MEANS OR ACTIVITIES.

---
###### 📌 THIS TAP IS _NOT OFFICAILLY ENDORSED_ BY [HOMEBREW](https://github.com/Homebrew).

