# openwrt-google-authenticator

Makefile for compiling the libpam version of Google Authenticator for OpenWrt 18.06.2.

OpenWrt SDK for the target is needed for compiling the binaries.

For using Google Authenticator with SSH, the openssh-server-pam package is needed.
Caution: Login via SSH and Google Authenticator will not be possible after restart without internet access (without NTP update).
