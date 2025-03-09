# Function: <code>proc_create_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463712,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:484",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "kernel/time/timer_stats.c:init_tstats_procfs",
        "kernel/dma.c:proc_dma_init",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "kernel/cgroup.c:cgroup_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/slab_common.c:slab_proc_init",
        "mm/vmalloc.c:proc_vmalloc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/rtc/rtc-proc.c:rtc_proc_add_device",
        "drivers/md/md.c:md_init",
        "net/core/sock.c:proto_init_net",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp_proc_register",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp_proc_register",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463712,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648256,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:489",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "kernel/time/timer_stats.c:init_tstats_procfs",
        "kernel/dma.c:proc_dma_init",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "kernel/cgroup.c:cgroup_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/slab_common.c:slab_proc_init",
        "mm/vmalloc.c:proc_vmalloc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add",
        "drivers/rtc/rtc-proc.c:rtc_proc_add_device",
        "drivers/md/md.c:md_init",
        "net/core/sock.c:proto_init_net",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp_proc_register",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp_proc_register",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648256,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736560,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "kernel/time/timer_stats.c:init_tstats_procfs",
        "kernel/dma.c:proc_dma_init",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "kernel/cgroup.c:cgroup_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/slab_common.c:slab_proc_init",
        "mm/vmalloc.c:proc_vmalloc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add",
        "drivers/rtc/rtc-proc.c:rtc_proc_add_device",
        "drivers/md/md.c:md_init",
        "net/core/sock.c:proto_init_net",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp_proc_register",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp_proc_register",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736560,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790432,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:475",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "kernel/dma.c:proc_dma_init",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/slab_common.c:slab_proc_init",
        "mm/vmalloc.c:proc_vmalloc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add",
        "drivers/rtc/rtc-proc.c:rtc_proc_add_device",
        "drivers/md/md.c:md_init",
        "net/core/sock.c:proto_init_net",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp_proc_register",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp_proc_register",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790432,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939760,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:477",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add",
        "drivers/rtc/rtc-proc.c:rtc_proc_add_device",
        "net/core/neighbour.c:neigh_table_init",
        "net/ipv4/tcp_ipv4.c:tcp_proc_register",
        "net/ipv4/udp.c:udp_proc_register",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939760,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124480,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:534",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124480,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582218944,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:536",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218944,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582383152,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383152,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582482064,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482064,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582781161,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:549",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_create"
      ],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780864,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582854617,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:569",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_create"
      ],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854320,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582882921,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:564",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_create"
      ],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882624,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583216537,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:564",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_create"
      ],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216240,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583713897,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:567",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_create"
      ],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713552,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325497,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:567",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_create"
      ],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325104,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584555545,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:566",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_create"
      ],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555152,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584787401,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:566",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_create"
      ],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787008,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494103864,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494103864,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227553624,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/atags_proc.c:init_atags_procfs",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add",
        "sound/core/info.c:snd_info_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227553624,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287772352,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/proc_powerpc.c:proc_ppc64_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287772352,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273590190,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273590190,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582450800,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450800,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582387968,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387968,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582441280,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441280,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct proc_dir_entry * proc_create_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops, void * data)
```

```json
{
  "name": "proc_create_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582521456,
      "name": "proc_create_data",
      "external": true,
      "loc": "fs/proc/generic.c:537",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "fs/proc/generic.c:proc_create",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init_proc_interface",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_proc_host_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521456,
      "name": "proc_create_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct proc_ops * proc_ops</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct file_operations * proc_fops</code>
</li>
</ul>
</details>
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
