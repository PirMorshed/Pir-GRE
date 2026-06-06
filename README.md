README Introduction
Pir-GRE

Pir-GRE is a powerful Bash-based solution for deploying and managing GRE tunnels between Iran and foreign servers. The project automates tunnel creation, port forwarding, service management, MTU tuning, and tunnel regeneration using Systemd services and IPTables.

Designed for simplicity and reliability, PIR-GRE offers a fully interactive terminal interface that allows administrators to configure, maintain, and troubleshoot GRE infrastructures without manually editing network configurations.

=========================================================================================

### Fast Setup 
```bash
curl -sSL https://raw.githubusercontent.com/PirMorshed/Pir-GRE/main/Pir-GRE.sh -o Pir-GRE.sh && chmod +x Pir-GRE.sh && ./Pir-GRE.sh
```
=========================================================================================

### نصب سریع اسکریپت
```bash
curl -sSL https://raw.githubusercontent.com/PirMorshed/Pir-GRE/main/Pir-GRE.sh -o Pir-GRE.sh && chmod +x Pir-GRE.sh && ./Pir-GRE.sh
```
این اسکریپت با بازنویسی کامل و جایگزینی IPTables به جای fork و socat، به شدت سبک‌سازی شده و اکنون در ترافیک‌های سنگین و تعداد کاربران بالا، عملکرد فوق‌العاده‌ای ارائه می‌دهد. با حل کامل مشکلات مصرف CPU و RAM، این ابزار پایداری سرور شما را تضمین می‌کند. علاوه بر این، با استفاده از بخش‌های مدیریتی و بهینه‌سازی پروتکل TCP، می‌توانید حتی در شدیدترین اختلالات شبکه نیز ارتباطی پایدار و بدون افت کیفیت داشته باشید.

📌 این نسخه، ورژن اختصاصی و Custom شده برای PirMorshed است.

=========================================================================================

### Features 
✅ Interactive CLI Interface

Easy-to-use menu system
Real-time action logs
Automatic validation of user inputs

✅ GRE Tunnel Management

Create GRE tunnels between Iran and Foreign servers
Automatic IP assignment
Automatic GRE key generation
Persistent Systemd services

✅ Port Forwarding

TCP forwarding
UDP forwarding
Single port support
Multiple ports support
Port range support
IPTables Kernel-Space forwarding

✅ Service Management

Start services
Stop services
Restart services
Enable on boot
Disable services
Service status monitoring

✅ MTU Management

Custom MTU during installation
Change MTU after deployment
Automatic Systemd service updates

✅ Automation System

Scheduled GRE regeneration
Cron-based automation
Timezone synchronization
Tunnel recreation scripts
Automatic service restoration

✅ Backup & Recovery

Automatic service backup
GRE configuration recovery
Forwarder recovery
Systemd backup management

✅ Cleanup Tools

Full GRE removal
Forwarder cleanup
Systemd cleanup
Route cleanup
Conntrack cleanup
Automation cleanup

✅ Network Optimization

RP Filter handling
IP Forwarding management
Persistent GRE interfaces
Automatic route maintenance
Requirements
Ubuntu / Debian
Root Access
Systemd
iproute2
iptables

=========================================================================================

Supported Configurations
Iran Server ↔ Foreign Server
Multiple GRE Tunnels
Multiple Port Forwarders
TCP & UDP Traffic
Custom MTU
Automated Tunnel Rotation

=========================================================================================
gre
gre-tunnel
gre-network
iptables
nat
dnat
udp-forwarding
tcp-forwarding
systemd
bash-script
linux-networking
server-automation
iran-server
tunnel-management

