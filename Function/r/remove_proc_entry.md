# Function: <code>remove_proc_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464880,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:549",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_stats_proc_exit",
        "fs/jbd2/journal.c:jbd2_stats_proc_exit",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/rtc-proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/packet/af_packet.c:packet_net_exit",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464880,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649264,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:554",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_stats_proc_exit",
        "fs/jbd2/journal.c:jbd2_stats_proc_exit",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/rtc-proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/packet/af_packet.c:packet_net_exit",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649264,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581737568,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:556",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/rtc-proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/packet/af_packet.c:packet_net_exit",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581737568,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791520,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:540",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/rtc-proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/packet/af_packet.c:packet_net_exit",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791520,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940896,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:550",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/rtc-proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940896,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125376,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:652",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/rtc-proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125376,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219840,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:654",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219840,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582384048,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384048,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582482960,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482960,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582782080,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:668",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782080,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582855536,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:688",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582855536,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582883776,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:683",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582883776,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217392,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:683",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/packet/af_packet.c:packet_net_exit",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217392,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583714880,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:686",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/packet/af_packet.c:packet_net_exit",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714880,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584326544,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:686",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:journal_exit",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/packet/af_packet.c:packet_net_exit",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584326544,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584556592,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:685",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:journal_exit",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/packet/af_packet.c:packet_net_exit",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556592,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788448,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:685",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:journal_exit",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/packet/af_packet.c:packet_net_exit",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788448,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494105296,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494105296,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227554744,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/mtd/mtdcore.c:cleanup_mtd",
        "drivers/mtd/mtdcore.c:init_mtd",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227554744,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287773776,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287773776,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273587480,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273587480,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451696,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451696,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388864,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388864,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582442176,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/netfilter/nfnetlink_queue.c:nfnl_queue_net_exit",
        "net/netfilter/nfnetlink_log.c:nfnl_log_net_exit",
        "net/netfilter/nf_conntrack_standalone.c:nf_conntrack_pernet_exit",
        "net/netfilter/nf_conntrack_standalone.c:nf_conntrack_pernet_exit",
        "net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_pernet_fini",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442176,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void remove_proc_entry(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "remove_proc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582522352,
      "name": "remove_proc_entry",
      "external": true,
      "loc": "fs/proc/generic.c:655",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "kernel/irq/proc.c:unregister_irq_proc",
        "fs/proc/proc_tty.c:proc_tty_unregister_driver",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "crypto/proc.c:crypto_exit_proc",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/char/misc.c:misc_init",
        "drivers/connector/connector.c:cn_fini",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_exit_procfs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_rm",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/input/input.c:input_proc_exit",
        "drivers/rtc/proc.c:rtc_proc_del_device",
        "drivers/md/md.c:md_exit",
        "net/core/sock.c:proto_exit_net",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/net-procfs.c:dev_mc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_exit",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_exit",
        "net/netlink/af_netlink.c:netlink_net_exit",
        "net/netfilter/core.c:netfilter_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/route.c:ip_rt_do_proc_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net",
        "net/ipv4/raw.c:raw_exit_net",
        "net/ipv4/udp.c:udp4_proc_exit_net",
        "net/ipv4/udplite.c:udplite4_proc_exit_net",
        "net/ipv4/arp.c:arp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_exit",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/proc.c:ip_proc_exit_net",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_fini",
        "net/unix/af_unix.c:unix_net_exit",
        "net/ipv6/anycast.c:ac6_proc_exit",
        "net/ipv6/addrconf.c:if6_proc_net_exit",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/route.c:ip6_route_net_exit_late",
        "net/ipv6/udp.c:udp6_proc_exit",
        "net/ipv6/udplite.c:udplite6_proc_exit_net",
        "net/ipv6/raw.c:raw6_exit_net",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_exit",
        "net/ipv6/ping.c:ping_v6_proc_exit_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/ipv6/proc.c:ipv6_proc_exit_net",
        "net/wireless/wext-proc.c:wext_proc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582522352,
      "name": "remove_proc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
