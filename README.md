------Day 7 (17/11/2025)

1.Command: sudo apt install tree
2025-11-17T09:36:16.091963+00:00 ASHOKKUMAR systemd-resolved[124]: Clock change detected. Flushing caches.
2025-11-17T09:36:20.748426+00:00 ASHOKKUMAR dbus-daemon[191]: [system] Activating via systemd: service name='org.freedesktop.PackageKit' unit='packagekit.service' requested by ':1.17' (uid=0 pid=3046 comm="/usr/bin/gdbus call --system --dest org.freedeskto" label="kernel")
2025-11-17T09:36:20.758489+00:00 ASHOKKUMAR systemd[1]: Reached target network-online.target - Network is Online.
2025-11-17T09:36:20.798794+00:00 ASHOKKUMAR systemd[1]: Starting packagekit.service - PackageKit Daemon...
2025-11-17T09:36:20.822099+00:00 ASHOKKUMAR PackageKit: daemon start
2025-11-17T09:36:20.909405+00:00 ASHOKKUMAR dbus-daemon[191]: [system] Activating via systemd: service name='org.freedesktop.PolicyKit1' unit='polkit.service' requested by ':1.19'
2025-11-17T09:36:20.937814+00:00 ASHOKKUMAR systemd[1]: Starting polkit.service - Authorization Manager...
2025-11-17T09:36:21.024387+00:00 ASHOKKUMAR polkitd[3055]: Started polkitd version 124
2025-11-17T09:36:21.048834+00:00 ASHOKKUMAR dbus-daemon[191]: [system] Successfully activated service 'org.freedesktop.PackageKit'
2025-11-17T09:36:21.049376+00:00 ASHOKKUMAR systemd[1]: Started packagekit.service - PackageKit Daemon.
2025-11-17T09:36:42.518860+00:00 ASHOKKUMAR systemd-resolved[124]: Clock change detected. Flushing caches.

2.Command: tree
2025-11-17T09:38:41.951334+00:00 ASHOKKUMAR systemd-resolved[124]: Clock change detected. Flushing caches.
2025-11-17T09:38:50.985413+00:00 ASHOKKUMAR wsl-pro-service[201]: #033[36mINFO#033[0m Daemon: connecting to Windows Agent
2025-11-17T09:38:50.985680+00:00 ASHOKKUMAR wsl-pro-service[201]: #033[37mDEBUG#033[0m Updated systemd status to "Connecting"
2025-11-17T09:38:51.016737+00:00 ASHOKKUMAR wsl-pro-service[201]: #033[33mWARNING#033[0m Daemon: could not connect to Windows Agent: could not get address: could not read agent port file "/mnt/c/Users/ashok/.ubuntupro/.address": open /mnt/c/Users/ashok/.ubuntupro/.address: no such file or directory
2025-11-17T09:38:51.016834+00:00 ASHOKKUMAR wsl-pro-service[201]: #033[36mINFO#033[0m Reconnecting to Windows host in 60 seconds
2025-11-17T09:38:51.016872+00:00 ASHOKKUMAR wsl-pro-service[201]: #033[37mDEBUG#033[0m Updated systemd status to "Not connected: waiting to retry"

3.Command: mkdir
2025-11-17T09:39:41.783672+00:00 ASHOKKUMAR systemd-resolved[124]: Clock change detected. Flushing caches.
2025-11-17T09:39:50.896505+00:00 ASHOKKUMAR wsl-pro-service[201]: INFO Daemon: connecting to Windows Agent
2025-11-17T09:39:50.933605+00:00 ASHOKKUMAR wsl-pro-service[201]: WARNING Missing Windows Agent port file "/mnt/c/Users/ashok/.ubuntupro/.address"
2025-11-17T09:40:11.669579+00:00 ASHOKKUMAR systemd-resolved[124]: Clock change detected. Flushing caches.


