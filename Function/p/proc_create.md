# Function: <code>proc_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "proc_create",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595013289,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "arch/x86/kernel/cpu/mtrr/if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595079747,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/exec_domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exec_domain.c:proc_execdomains_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595080302,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595091408,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/sched/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stats.c:proc_schedstat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595091442,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:init_sched_debug_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579771380,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:init_irq_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587336487,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595099938,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:init_timer_list_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595100809,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/time/timer_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_stats.c:init_tstats_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595101234,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma.c:proc_dma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595101739,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:proc_modules_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595102150,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:kallsyms_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595106166,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595132293,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595137646,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595141429,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:proc_vmalloc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595144841,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:procswaps_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595158702,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:proc_filesystems_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595165260,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:proc_locks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595166967,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/proc_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167029,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/cmdline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/cmdline.c:proc_cmdline_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167063,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/consoles.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/consoles.c:proc_consoles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167097,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/cpuinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/cpuinfo.c:proc_cpuinfo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167131,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/devices.c:proc_devices_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167165,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/interrupts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/interrupts.c:proc_interrupts_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167199,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/loadavg.c:proc_loadavg_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167233,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:proc_meminfo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167267,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:proc_stat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167301,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:proc_uptime_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167335,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/version.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/version.c:proc_version_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167369,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/softirqs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/softirqs.c:proc_softirqs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167526,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595170463,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595170713,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/kmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kmsg.c:proc_kmsg_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595170750,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595170845,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "fs/proc/version_signature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/version_signature.c:proc_version_signature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595196507,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595206102,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "crypto/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/proc.c:crypto_init_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595209852,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595226785,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595229268,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595235202,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_sleep_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595254621,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595262110,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/char/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/misc.c:misc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584357640,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/connector/connector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595289198,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/scsi/scsi_devinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595289333,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/scsi/scsi_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_proc.c:scsi_init_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595290034,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595302548,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595309107,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586190054,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586413126,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586459734,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:psched_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586491766,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586520102,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586527878,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586728582,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586759174,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586797974,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586846342,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586866982,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv4/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586876459,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586960534,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/xfrm/xfrm_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_proc.c:xfrm_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586961752,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586989142,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ac6_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587013030,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:if6_proc_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587054502,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587124518,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587141786,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587193382,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587207697,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587228598,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/ipv6/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587245255,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587277478,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:30",
      "file": "net/wireless/wext-proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-proc.c:wext_proc_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "proc_create",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595177944,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "arch/x86/kernel/cpu/mtrr/if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595246424,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/exec_domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exec_domain.c:proc_execdomains_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595247621,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595259029,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/sched/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stats.c:proc_schedstat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595259099,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:init_sched_debug_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579794548,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:init_irq_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587835262,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595267982,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:init_timer_list_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595268795,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/time/timer_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_stats.c:init_tstats_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595269223,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma.c:proc_dma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595269698,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:proc_modules_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595271012,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:kallsyms_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595275527,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595302897,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595308249,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595312508,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:proc_vmalloc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595316038,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:procswaps_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595332261,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:proc_filesystems_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595338941,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:proc_locks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341388,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/proc_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341450,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/cmdline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/cmdline.c:proc_cmdline_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341484,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/consoles.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/consoles.c:proc_consoles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341518,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/cpuinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/cpuinfo.c:proc_cpuinfo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341552,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/devices.c:proc_devices_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341586,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/interrupts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/interrupts.c:proc_interrupts_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341620,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/loadavg.c:proc_loadavg_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341654,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:proc_meminfo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341688,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:proc_stat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341722,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:proc_uptime_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341756,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/version.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/version.c:proc_version_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341790,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/softirqs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/softirqs.c:proc_softirqs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341947,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595344979,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595345209,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/kmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kmsg.c:proc_kmsg_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595345246,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595345341,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/version_signature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/version_signature.c:proc_version_signature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595371614,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595381758,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "crypto/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/proc.c:crypto_init_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595386910,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595404920,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595407440,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595415076,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_sleep_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595435740,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595443378,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/char/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/misc.c:misc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584691784,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/connector/connector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595472037,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/scsi/scsi_devinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595472179,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/scsi/scsi_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_proc.c:scsi_init_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595472881,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595485672,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595492379,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586610822,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586856198,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586905830,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:psched_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586937270,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586962566,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586970454,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587176550,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587207206,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587246982,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587296102,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587316758,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587324977,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587406854,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/xfrm/xfrm_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_proc.c:xfrm_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587408072,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587435782,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ac6_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587459798,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:if6_proc_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587502758,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587575814,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587594474,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648470,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664513,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587685702,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587709015,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587743158,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/wireless/wext-proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-proc.c:wext_proc_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "proc_create",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595421156,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "arch/x86/kernel/cpu/mtrr/if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595490355,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/exec_domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exec_domain.c:proc_execdomains_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595491786,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595503972,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/sched/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stats.c:proc_schedstat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595504042,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:init_sched_debug_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821748,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:init_irq_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588050548,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595512505,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:init_timer_list_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595514480,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/time/timer_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_stats.c:init_tstats_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595514911,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma.c:proc_dma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595515470,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:proc_modules_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595516784,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:kallsyms_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595521917,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595551291,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595556502,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595560810,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:proc_vmalloc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595564327,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:procswaps_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595580438,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:proc_filesystems_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595587195,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:proc_locks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589734,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/proc_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589796,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/cmdline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/cmdline.c:proc_cmdline_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589830,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/consoles.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/consoles.c:proc_consoles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589864,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/cpuinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/cpuinfo.c:proc_cpuinfo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589898,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/devices.c:proc_devices_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589932,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/interrupts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/interrupts.c:proc_interrupts_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589966,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/loadavg.c:proc_loadavg_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595590000,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:proc_meminfo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595590034,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:proc_stat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595590068,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:proc_uptime_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595590102,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/version.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/version.c:proc_version_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595590136,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/softirqs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/softirqs.c:proc_softirqs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595590293,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595593325,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595593555,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/kmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kmsg.c:proc_kmsg_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595593592,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595593687,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/version_signature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/version_signature.c:proc_version_signature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595619960,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595630054,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "crypto/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/proc.c:crypto_init_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595635302,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595654878,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595657355,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595664894,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_sleep_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595688092,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595695730,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/char/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/misc.c:misc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584878344,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/connector/connector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595724758,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/scsi/scsi_devinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595724900,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/scsi/scsi_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_proc.c:scsi_init_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595725602,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595738687,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595745417,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586795174,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587047318,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587100118,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:psched_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587132454,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587157462,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587165350,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587376710,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587407622,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587447590,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587498166,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587519334,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587527649,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587610230,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/xfrm/xfrm_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_proc.c:xfrm_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587611464,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587639158,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ac6_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663318,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:if6_proc_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587707174,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587779862,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587799466,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587855014,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587872977,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587894294,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587923431,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587958374,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/wireless/wext-proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-proc.c:wext_proc_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "proc_create",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596341262,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "arch/x86/kernel/cpu/mtrr/if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596411417,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/exec_domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exec_domain.c:proc_execdomains_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596412918,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596424012,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/sched/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stats.c:proc_schedstat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596424092,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:init_sched_debug_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820436,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:init_irq_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277700,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596433290,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:init_timer_list_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596434733,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma.c:proc_dma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596435325,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:proc_modules_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596435741,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:kallsyms_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596440788,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596477102,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596483226,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596487701,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:proc_vmalloc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596491515,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:procswaps_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596508094,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:proc_filesystems_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596517047,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:proc_locks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519615,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/proc_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519682,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/cmdline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/cmdline.c:proc_cmdline_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519721,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/consoles.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/consoles.c:proc_consoles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519760,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/cpuinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/cpuinfo.c:proc_cpuinfo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519799,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/devices.c:proc_devices_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519838,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/interrupts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/interrupts.c:proc_interrupts_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519877,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/loadavg.c:proc_loadavg_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519916,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:proc_meminfo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519955,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:proc_stat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596519994,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:proc_uptime_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596520033,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/version.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/version.c:proc_version_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596520072,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/softirqs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/softirqs.c:proc_softirqs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596520254,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:proc_kcore_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596523246,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596523467,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/kmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kmsg.c:proc_kmsg_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596523509,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596523609,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "fs/proc/version_signature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/version_signature.c:proc_version_signature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596550470,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596562321,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "crypto/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/proc.c:crypto_init_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596567322,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596576680,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596579667,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596588386,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_sleep_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596612442,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596620280,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/char/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/misc.c:misc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584967256,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/connector/connector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596650473,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/scsi/scsi_devinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596650614,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/scsi/scsi_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_proc.c:scsi_init_procfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596651331,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596666916,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596673847,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586918550,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587175014,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587228198,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:psched_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587262790,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587288838,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587297206,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587510774,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587543334,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587584246,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587635206,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587657414,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587673664,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587759446,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/xfrm/xfrm_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_proc.c:xfrm_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587760658,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587788678,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ac6_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587812502,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:if6_proc_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587857862,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587936502,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587956058,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588011654,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588029581,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588051558,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/ipv6/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588081191,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588116454,
      "name": "proc_create",
      "external": false,
      "loc": "include/linux/proc_fs.h:31",
      "file": "net/wireless/wext-proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-proc.c:wext_proc_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939936,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:511",
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
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/md/md.c:md_init",
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/sched/sch_api.c:psched_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
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
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939936,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124560,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:550",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124560,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219024,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:552",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219024,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383232,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383232,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582482144,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_ptc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482144,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582781120,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:564",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_ptc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582781120,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582854576,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:584",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854576,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582882880,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:579",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882880,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583216496,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:579",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216496,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583713856,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:582",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/module/procfs.c:proc_modules_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713856,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584325456,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:582",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/module/procfs.c:proc_modules_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325456,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584555504,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:581",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/module/procfs.c:proc_modules_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555504,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct proc_ops * proc_ops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787360,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:581",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/module/procfs.c:proc_modules_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/kallsyms.c:kallsyms_init",
        "kernel/latencytop.c:init_lstats_procfs",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787360,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494103984,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494103984,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227553708,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/alignment.c:alignment_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227553708,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287772464,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtasd.c:rtas_init",
        "arch/powerpc/kernel/rtas-proc.c:proc_rtas_init",
        "arch/powerpc/kernel/rtas-proc.c:proc_rtas_init",
        "arch/powerpc/kernel/rtas-proc.c:proc_rtas_init",
        "arch/powerpc/kernel/rtas-proc.c:proc_rtas_init",
        "arch/powerpc/kernel/rtas-proc.c:proc_rtas_init",
        "arch/powerpc/mm/numa.c:topology_update_init",
        "arch/powerpc/platforms/pseries/lpar.c:__machine_initcall_pseries_vcpudispatch_stats_procfs_init",
        "arch/powerpc/platforms/pseries/lpar.c:__machine_initcall_pseries_vcpudispatch_stats_procfs_init",
        "arch/powerpc/platforms/pseries/reconfig.c:__machine_initcall_pseries_proc_ppc64_create_ofdt",
        "arch/powerpc/platforms/pseries/lparcfg.c:__machine_initcall_pseries_lparcfg_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287772464,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273590288,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273590288,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450880,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450880,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388048,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388048,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441360,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441360,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```

```json
{
  "name": "proc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521536,
      "name": "proc_create",
      "external": true,
      "loc": "fs/proc/generic.c:553",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_ptc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_prof_cpu_mask",
        "kernel/module.c:proc_modules_init",
        "kernel/kallsyms.c:kallsyms_init",
        "kernel/latencytop.c:init_lstats_procfs",
        "mm/slab_common.c:slab_proc_init",
        "mm/swapfile.c:procswaps_init",
        "fs/proc/cpuinfo.c:proc_cpuinfo_init",
        "fs/proc/stat.c:proc_stat_init",
        "fs/proc/kcore.c:proc_kcore_init",
        "fs/proc/vmcore.c:vmcore_init",
        "fs/proc/kmsg.c:proc_kmsg_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/page.c:proc_page_init",
        "fs/proc/version_signature.c:proc_version_signature_init",
        "drivers/acpi/proc.c:acpi_sleep_proc_init",
        "drivers/tty/sysrq.c:sysrq_init",
        "drivers/scsi/scsi_devinfo.c:scsi_init_devinfo",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "drivers/input/input.c:input_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521536,
      "name": "proc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct proc_dir_entry * proc_create(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct file_operations * proc_fops)
```
</details>
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
