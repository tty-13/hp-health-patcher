# hp-health patcher (for Debian 12)

I had some trouble finding relevant info so I made a repo with this, since many homelab and small server owners have perfectly functional hardware that HPE decided to deprecate, hide away the packages and remove the documentation from their website.

This should work on most Gen8/Gen9 Proliant servers, it will download hp-health from HPE's repo, patch the .deb to allow its installation, then install HPE Agentless Management Software along with HPONCFG online configuration tool.

HP/HPE software are distributed under proprietary licenses, see their website for the EULA. 
This script here is licensed under GNU GPL v3