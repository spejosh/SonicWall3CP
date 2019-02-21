# SonicWall3CP
## Dell SonicWall Content Pack for GrayLog 3
This content pack include the following:
* SonicWall VPN Audit (24hr) - Dashboard
  * Includes successfull vpn connection stats
  * Includes failed connection stats
* SonicWall Input
  * Raw/Plaintext UDP on port 12205
  * 11 Extractors that parse the default SonicWall syslog messages for information
* SonicWall VPN Steam
  * Graylog Stream that collects all syslog messages that contain 'VPN' in the 'msg' field


## How to use
1. Configure your SonicWall to forward Syslog to your graylog instance on UDP Port 12205.
1. Update Steam rules to capture SonicWall VPN messages.
