## TESTED VPS
     * DIGITALOCEAN (DEBIAN 10/11)
     * AWS (DEBIAN 10 / UBUNTU - SSH WS NOT WORKING ON UBUNTU)
     * OVH (DEBIAN 10/11) (REQ root Akses)
     * IDCLOUDHOST (REQ root Akses)
     
### RECOMMENDATION OS
     * DEBIAN 10

## YOU CAN USE THIS TO GET ROOT AKSES
<pre></code>sudo su && wget https://raw.githubusercontent.com/anzclan/ovh-root/main/root && bash root</code></pre>

### INSTALATION
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade -y && apt install curl -y && apt install -y wget screen && wget https://raw.githubusercontent.com/ZvnStores/zzz/main/install.sh && chmod +x install.sh && ./install.sh</code></pre>

## VERSION
V3.0
