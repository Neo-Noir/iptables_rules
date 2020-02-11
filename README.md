# iptables_rules
Various rulesets for iptables

OSCP base: OffSec tells you to protect yourself from other students.....but gives you zero clues about how to do it! This ruleset (customized with some actual IP addresses pertaining to your situation) is a good start. Make sure you configure NetworkManager or systemd-networkd to automatically load your rules whenever an interface comes up! Also, if you're running on Windows, you can set your network interface for the VM to NAT, and create outbound Windows Firewall rules for %SystemRoot%\SysWOW64\vmnat.exe to provide a "safety", to make sure things aren't escaping.
