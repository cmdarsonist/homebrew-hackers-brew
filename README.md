# Hackers' 🍺 Brew 
> *A Homebrew / Linuxbrew tap to install InfoSec and Hacking Tools and Utilities on Linux, BSD, and macOS.*

🎯 The **objective** of this tap is to simplify the distribution of **InfoSec / Hacking tools and utilities** on **a wide-range of Linux Distros** and **macOS**. 

**_Theres also an intention to support BSD but currently, it is very experimental. Progress is dependant on LinuxBrew support with BSD._**

---
### 🤔 Wait, why Homebrew 🍻?
**Homebrew** 🍻 is one of the few **package 📦 managers**  that is aiming to **support multiple OSs (i.e.
macOS, Linux, WSL, BSD)**.

👉 Utilizing **Homebrew** 🍻 and **this tap**, we intend to **provide 🎁 users** with **OS agnostic solution to install, setup, and deploy their InfoSec / Hacking toolbelt** through the use of a single uniform tool 🔧.

## 💾 Install
```bash
brew tap open-arsenal/hackers-brew
```
🖐 *If it's not obvious*, you **must** have first installed 👉 [**Homebrew (on macOS)**](https://docs.brew.sh/Installation) **or** 👉 [**Linuxbrew (on Linux)**](https://docs.brew.sh/Homebrew-on-Linux). 

**👉 For BSD, [may try these instructions to install Homebrew; which are translated to English.](https://translate.google.com/translate?hl=en&sl=ja&u=https://qiita.com/cielavenir/items/741921fcecb281555f77&prev=search)** [[Original Link in Japanese](https://qiita.com/cielavenir/items/741921fcecb281555f77)]

### 🛡 Prepare Your System
If you haven't taken any steps in securing your OS, we recommend you take a look at the following guides and do whatever you deem necessary:

- 💪 **macOS**: [@drduh's](https://github.com/drduh) [masOS Security and Privacy Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
- 💪 **Linux (Debian)**: [@drduh's](https://github.com/drduh) [Debian Security and Privacy Guide](https://github.com/drduh/Debian-Privacy-Server-Guide)

## 🤷‍♂️ Already on Homebrew?
There's already several useful binaries and applications available on **Homebrew's Offical Taps 👍**. _These you won't find 👀 in this repo. Any updates we have are usally already contributed to Homebrew 🍻._

👉 Below you'll find a list of tools spotted in **The Offical Homebrew Tap 👍**.

- `aircrack-ng` - `Next-generation aircrack with lots of new features`
- `algernon` - `Pure Go web server with Lua, Markdown, HTTP/2 and template support`
- `apib` - `HTTP performance-testing tool`
- `apt-dater` - `Manage package updates on remote hosts using SSH`
- `arp-scan` - `ARP scanning and fingerprinting tool`
- `arp-sk` - `ARP traffic generation tool`
- `arping` - `Utility to check whether MAC addresses are already taken on a LAN`
- `arpoison` - `UNIX arp cache update utility`
- `armour` - `Uncomplicated, modern HTTP server`
- `assh` - `Advanced SSH config - Regex, aliases, gateways, includes and dynamic hosts`
- `autossh` - `Automatically restart SSH sessions and tunnels`
- `aws-keychain` - `Uses macOS keychain for storage of AWS credentials`
- `caddy` - `Alternative general-purpose HTTP/2 web server`
- `certbot` - `Tool to obtain certs from Let's Encrypt and autoenable HTTPS`
- `clam-av` - `Anti-virus software`
- `connect` - `Provides SOCKS and HTTPS proxy support to SSH`
- `corkscrew` - `Tunnel SSH through HTTP proxies`
- `csshx` - `Cluster ssh tool for Terminal.app`
- `curl` - `Get a file from an HTTP, HTTPS or FTP server`
- `curl-openssl` - `Get a file from an HTTP, HTTPS or FTP server`
- `darkhttpd` - `Small static webserver without CGI`
- `dropbear` - `Small SSH server/client for POSIX-based system`
- `dsh` - `Dancer's shell, or distributed shell`
- `duo_unix` - `Two-factor authentication for SSH`
- `exploitdb` - `The official Exploit Database`
- `fabio` - `Zero-conf load balancing HTTP(S) router`
- `fabric` - `Library and command-line tool for SSH`
- `fail2ban` - `Scan log files and ban IPs showing malicious signs`
- `fortio` - `HTTP and gRPC load testing and visualization tool and server`
- `git-remote-gcrypt` - `GPG-encrypted git remotes`
- `git-ssh` - `Proxy for serving git repositories over SSH`
- `github-keygen` - `Bootstrap GitHub SSH configuration`
- `gor` - `Real-time HTTP traffic replay tool written in Go`
- `gssh` - `SSH automation tool based on Groovy DSL`
- `gnunet` - `Framework for distributed, secure and privacy-preserving applications`
- `gpgme` - `Library access to GnuPG`
- `gnupg` - `GNU Pretty Good Privacy (PGP) package`
- `h2o` - `HTTP server with support for HTTP/1.x and HTTP/2`
- `haproxy` - `Reliable, high performance TCP/HTTP load balancer`
- `hey` - `HTTP load generator, ApacheBench (ab) replacement`
- `hopenpgp-tools` - `Command-line tools for OpenPGP-related operations`
- `hss` - `Interactive parallel SSH client`
- `http-parser` - `HTTP request/response parser for c`
- `http-server` - `Simple zero-configuration command-line HTTP server`
- `http_load` - `Test throughput of a web server by running parallel fetches`
- `httpd` - `Apache HTTP server`
- `httpdiff` - `Compare two HTTP(S) responses`
- `httperf` - `Tool for measuring webserver performance`
- `httpflow` - `Packet capture and analysis utility similar to tcpdump for HTTP`
- `httpie` - `User-friendly cURL replacement (command-line HTTP client)`
- `httping` - `Ping-like tool for HTTP requests`
- `httpry` - `Packet sniffer for displaying and logging HTTP traffic`
- `httptunnel` - `Tunnels a data stream in HTTP requests` 
- `ike-scan` - `Discover and fingerprint IKE hosts`
- `keepkey-agent` - `Keepkey Hardware-based SSH/GPG agent` (same as `trezor-agent`)
- `keychain` - `User-friendly front-end to ssh-agent(1)`
- `libevhtp` - `Create extremely-fast and secure embedded HTTP servers with ease`
- `libgpg-error` - `Common error values for all GnuPG components`
- `libhttpserver` - `C++ library of embedded Rest HTTP server`
- `libhttpseverywhere` - `Bring HTTPSEverywhere to desktop apps`
- `libssh` - `C library SSHv1/SSHv2 client and server protocols`
- `libssh2` - `C library implementing the SSH2 protocol`
- `libmicrohttpd` - `Light HTTP/1.1 server library`
- `libyubikey` - `C library for manipulating Yubico one-time passwords`
- `lightpd` - `Small memory footprint, flexible web-server`
- `neon` - `HTTP and WebDAV client library with a C interface`
- `net-snmp` - `Implements SNMP v1, v2c, and v3, using IPv4 and IPv6`
- `netcat` - `Utility for managing network connections`
- `netcat6` - `Rewrite of netcat that supports IPv6, plus other improvements`
- `netdata` - `Distributed real-time performance and health monitoring`
- `nethogs` - `Net top tool grouping bandwidth per process`
- `netpref` - `Benchmarks performance of many different types of networking`
- `nettle` - `Low-level cryptographic library`
- `nghttp2` - `HTTP/2 C Library`
- `nginx` - `HTTP(S) server and reverse proxy, and IMAP/POP3 proxy server`
- `masscan` - `TCP port scanner, scans entire Internet in under 5 minutes`
- `mergelog` - `Merges httpd logs from web servers behind round-robin DNS`
- `mighttpd2` - `HTTP server`
- `mitmproxy` - `Intercept, modify, replay, save HTTP/S traffic`
- `mockserver` - `Mock HTTP server and proxy`
- `monkeysphere` - `Use the OpenPGP web of trust to verify ssh connections`
- `mpssh` - `Mass parallel ssh`
- `openldap` - `Open source suite of directory software`
- `openssl` - `Cryptography and SSL/TLS Toolkit`
- `pam_yubico` - `Yubico pluggable authentication module`
- `paperkey` - `Extract just secret information out of OpenPGP secret keys`
- `pgpdump` - `PGP packet visualizer`
- `pinentry-mac` - `Pinentry for GPG on Mac`
- `pius` - `PGP individual UID signer`
- `proxytunnel` - `Create TCP tunnels through HTTPS proxies`
- `putty` - `Implementation of Telnet and SSH`
- `qtkeychain` - `Platform-independent Qt API for storing passwords securely`
- `rinetd` - `Internet TCP redirection server`
- `rmate` - `Edit files from an SSH session in TextMate`
- `rssh` - `Restricted shell for use with OpenSSH`
- `scm-manager` - `Manage Git, Mercurial, and Subversion repos over HTTP`
- `serve` - `Static http server anywhere you need one`
- `siege` - `HTTP regression testing and benchmarking utility`
- `shmcat` - `Tool that dumps shared memory segments (System V and POSIX)`
- `slowhttptest` - `Simulates application layer denial of service attacks`
- `speedtest-cli` - `Command-line interface for https://speedtest.net bandwidth tests`
- `sproxy` - `HTTP proxy server collecting URLs in a 'siege-friendly' manner`
- `squid` - `Advanced proxy caching server for HTTP, HTTPS, FTP, and Gopher`
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
- `subnetcalc` - `IPv4/IPv6 subnet calculator`
- `synscan` - `Asynchronous half-open TCP portscanner`
- `teleport` - `Modern SSH server for teams managing distributed infrastructure`
- `telnet` - `User interface to the TELNET protocol (built from macOS Sierra sources)`
- `telnetd` - `TELNET server (built from macOS Sierra sources)`
- `tinyproxy` - `HTTP/HTTPS proxy for POSIX systems`
- `trafficserver` - `HTTP/1.1 compliant caching proxy server`
- `trezor-agent` - `Hardware SSH/GPG agent for Trezor, Keepkey & Ledger` (same as `keepkey-agent`)
- `tsung` - `Load testing for HTTP, PostgreSQL, Jabber, and others`
- `twtxt` - `Decentralised, minimalist microblogging service for hackers`
- `udpxy` - `UDP-to-HTTP multicast traffic relay daemon`
- `urh` - `Universal Radio Hacker`
- `varnish` - `High-performance HTTP accelerator`
- `vassh` - `Vagrant Host-Guest SSH Command Wrapper/Proxy/Forwarder`
- `vegeta` - `HTTP load testing tool and library`
- `wbox` - `HTTP testing tool and configuration-less HTTP server`
- `webfs` - `HTTP server for purely static content`
- `weighttp` - `Webserver benchmarking tool that supports multithreading`
- `whistle` - `HTTP, HTTP2, HTTPS, Websocket debugging proxy`
- `wiremock-standalone` - `Simulator for HTTP-based APIs`
- `wireshark` - `Graphical network analyzer and capture tool`
- `wirouter_keyrec` - `Recover the default WPA passphrases from supported routers`
- `wpscan` - `Black box WordPress vulnerability scanner`
- `wrk` - `HTTP benchmarking tool`
- `ykclient` - `Library to validate YubiKey OTPs against YubiCloud`
- `ykman` - `Tool for managing your YubiKey configuration`
- `ykpers` - `YubiKey personalization library and tool`
- `yubico-piv-tool` - `Command-line tool for the YubiKey PIV application`
- `zssh` - `Interactive file transfers over SSH`

---
👉 There's also some on available on **The Offical Homebrew Cask Tap 👍** as well. These are available to `macOS` users only.

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
It's true **"nothing lasts forever."** These tools 🛠 have run their course and for whatever reason be stopped being mantained and supported. 😵

## ✋ Requests
**Requests will be automatically closed.** If you want something added, 🙏 **submit a pull request**.

___
---
###### 🚨 DISCLAIMER: PLEASE NOTE 📝 EVERYTHING STORED IN THIS REPO IS AVAILABLE EXCLUSIVELY FOR ACADEMIC AND RESEARCH PURPOSES. THE MAINTAINERS AND CONTRIBUTORS DO NOT CONDONE THEIR USE IN ANY ILLEGAL MEANS OR ACTIVITIES.

---
###### 📌 THIS TAP IS _NOT OFFICAILLY ENDORSED_ BY [HOMEBREW](https://github.com/Homebrew).

