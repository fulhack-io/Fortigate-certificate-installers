# certbot-cloudflare-certificate-installers
Tools to install Let's Encrypt certificates which are created with certbot, using dns-01 challenge.

## Fortigate
The fortigate.sh script checks if there's a new certificate (with ExpiryDate newer than current certificatet), adds encryption to the privatekey, and uploads it into the fortigate.

**Installation**: Copy the fortigate.conf and fortigate.sh file into any map, the script will use the full path.

**Configuration**: Edit the fortigate.conf, set all values for your needs.

**Usage**: Start `fortigate.sh`.  Default configuration file is fortigate.conf.  You can use another configuration file as commandline option.
