# unixUser-
#include &lt;Constants.au3>  Global $unixUser = "user" Global $unixPassword = "password" Global $unixHost = "unixhost" Global $unixHostKey = "0x23,0x1234567890abcdef1234567890abcdef1234567890abcdef1234567890abcdef1234567890abcdef"  _writePuttyKnownHostKeyToRegistry($unixHost, $unixHostKey)  $sshCommand = "ls -la /tmp"
