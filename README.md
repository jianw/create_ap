## Dependencies

* bash (to run this script)
* util-linux (for getopt)
* hostapd
* dnsmasq
* iptables
* iproute2
* haveged (optional)

## Examples

### No passphrase (open network):

    ./create_ap wlan0 eth0 MyAccessPoint

### WPA + WPA2 passphrase:

    ./create_ap wlan0 eth0 MyAccessPoint MyPassPhrase

### AP without Internet sharing:

    ./create_ap -n wlan0 MyAccessPoint MyPassPhrase
