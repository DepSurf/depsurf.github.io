# Function: <code>is_vmalloc_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580740334,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585036172,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585191289,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:377",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580539941,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698869,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580725222,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580859518,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003631,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719918,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832885,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585421154,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585583396,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586244043,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586935793,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587266396,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587726061,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:481",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579297234,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580603973,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580764677,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580791067,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580929710,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582814574,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583972133,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585623807,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585771041,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586449259,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131025,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587467308,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587940383,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:468",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579295007,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580633893,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580801061,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830457,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974030,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582902314,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584020741,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585707535,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585857264,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586554942,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587261415,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587603788,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588083533,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:502",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579049269,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579315503,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715925,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580889765,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580921232,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581076670,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060410,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584236677,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586140063,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586296938,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587022462,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587780807,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588127852,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588628157,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:519",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579054043,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326404,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580848325,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025509,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057104,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215582,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261347,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584457199,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586391765,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586554414,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587319892,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123233,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588482814,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588997489,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:554",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579059153,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579350478,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917205,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581103029,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134896,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299358,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583379139,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584553727,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586533573,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586703278,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587500132,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588305489,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588677627,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589220497,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:582",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579066716,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579365620,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015365,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581167781,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200435,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369886,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583565938,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583853478,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584751587,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586779589,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586958936,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587775078,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588703392,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589090180,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589675528,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579069063,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579369860,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070645,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581225589,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258899,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424327,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583671670,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958917,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584886371,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585502089,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585858821,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586926005,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587158196,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587278465,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587318403,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587499546,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587544190,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587979654,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588230885,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588927264,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589314340,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589899800,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void * x)
```

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581625280,
      "name": "is_vmalloc_addr",
      "external": true,
      "loc": "mm/vmalloc.c:45",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "kernel/iomem.c:devm_memremap_release",
        "mm/util.c:kvfree_sensitive",
        "mm/util.c:vmemdup_user",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "security/apparmor/match.c:unpack_table",
        "security/apparmor/policy_unpack.c:deflate_compress",
        "block/blk-map.c:bio_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/md/dm-stats.c:dm_stats_delete",
        "drivers/md/dm-stats.c:dm_stats_delete",
        "drivers/md/dm-stats.c:dm_stats_delete",
        "drivers/md/dm-stats.c:dm_stats_delete",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap_skb",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625280,
      "name": "is_vmalloc_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool is_vmalloc_addr(const void * x)
```

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581671520,
      "name": "is_vmalloc_addr",
      "external": true,
      "loc": "mm/vmalloc.c:45",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/iomem.c:devm_memremap_release",
        "mm/util.c:kvfree_sensitive",
        "mm/util.c:vmemdup_user",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "security/apparmor/match.c:unpack_table",
        "security/apparmor/policy_unpack.c:deflate_compress",
        "block/blk-map.c:bio_map_kern",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/md/dm-stats.c:dm_stats_delete",
        "drivers/md/dm-stats.c:dm_stats_delete",
        "drivers/md/dm-stats.c:dm_stats_delete",
        "drivers/md/dm-stats.c:dm_stats_delete",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap_skb",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671520,
      "name": "is_vmalloc_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool is_vmalloc_addr(const void * x)
```

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581693744,
      "name": "is_vmalloc_addr",
      "external": true,
      "loc": "mm/vmalloc.c:58",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/iomem.c:devm_memremap_release",
        "mm/util.c:kvfree_sensitive",
        "mm/util.c:vmemdup_user",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/policy_unpack.c:deflate_compress",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693744,
      "name": "is_vmalloc_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool is_vmalloc_addr(const void * x)
```

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581965888,
      "name": "is_vmalloc_addr",
      "external": true,
      "loc": "mm/vmalloc.c:73",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/iomem.c:devm_memremap_release",
        "mm/util.c:kvfree_sensitive",
        "mm/util.c:vmemdup_user",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/policy_unpack.c:deflate_compress",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965888,
      "name": "is_vmalloc_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool is_vmalloc_addr(const void * x)
```

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582384432,
      "name": "is_vmalloc_addr",
      "external": true,
      "loc": "mm/vmalloc.c:75",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility",
        "arch/x86/kernel/ldt.c:map_ldt_struct",
        "arch/x86/mm/fault.c:page_fault_oops",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/iomem.c:devm_memremap_release",
        "mm/util.c:kvrealloc",
        "mm/util.c:kvfree_sensitive",
        "mm/util.c:vmemdup_user",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/usercopy.c:check_heap_object",
        "security/apparmor/match.c:unpack_table",
        "security/apparmor/match.c:unpack_table",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384432,
      "name": "is_vmalloc_addr",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool is_vmalloc_addr(const void * x)
```

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582888480,
      "name": "is_vmalloc_addr",
      "external": true,
      "loc": "mm/vmalloc.c:78",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility",
        "arch/x86/kernel/ldt.c:map_ldt_struct",
        "arch/x86/mm/fault.c:page_fault_oops",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/iomem.c:devm_memremap_release",
        "mm/util.c:kvrealloc",
        "mm/util.c:kvfree_sensitive",
        "mm/util.c:vmemdup_user",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/usercopy.c:check_heap_object",
        "security/apparmor/match.c:unpack_table",
        "security/apparmor/match.c:unpack_table",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888480,
      "name": "is_vmalloc_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool is_vmalloc_addr(const void * x)
```

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583103392,
      "name": "is_vmalloc_addr",
      "external": true,
      "loc": "mm/vmalloc.c:78",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility",
        "arch/x86/kernel/ldt.c:map_ldt_struct",
        "arch/x86/kernel/sev.c:__set_pages_state",
        "arch/x86/mm/fault.c:page_fault_oops",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/iomem.c:devm_memremap_release",
        "mm/util.c:kvrealloc",
        "mm/util.c:kvfree_sensitive",
        "mm/util.c:vmemdup_user",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/usercopy.c:check_heap_object",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103392,
      "name": "is_vmalloc_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool is_vmalloc_addr(const void * x)
```

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286016,
      "name": "is_vmalloc_addr",
      "external": true,
      "loc": "mm/vmalloc.c:78",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:map_ldt_struct",
        "arch/x86/kernel/sev.c:__set_pages_state",
        "arch/x86/mm/fault.c:page_fault_oops",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "mm/util.c:kvrealloc",
        "mm/util.c:kvfree_sensitive",
        "mm/util.c:vmemdup_user",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/usercopy.c:check_heap_object",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "drivers/md/dm-stats.c:message_stats_delete",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286016,
      "name": "is_vmalloc_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490344228,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/arm64/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/ioremap.c:iounmap"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492431724,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492614208,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492662268,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492826344,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495466000,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495780588,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497283644,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498050224,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498111508,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_init_fq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498161196,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498592456,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498690484,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:msm_handle_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498844196,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/iommu/dma-iommu.c:__iommu_dma_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498852916,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498910040,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/iommu/rockchip-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499889404,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500000324,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500033384,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500234272,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500385760,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500436040,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500639852,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500689300,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501223760,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501492168,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/firmware/qcom_scm-64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/qcom_scm-64.c:qcom_scm_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501687216,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502520776,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502950432,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503619528,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_set_status",
        "net/packet/af_packet.c:__packet_set_status",
        "net/packet/af_packet.c:__packet_set_status"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226307936,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226465872,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 3226501328,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 3226632200,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 3228832616,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 3229132632,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 3230459940,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230814796,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230922440,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231224832,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 3231304760,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:msm_handle_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 3231448916,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3231467448,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/iommu/omap-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/omap-iommu.c:omap_iommu_attach_dev",
        "drivers/iommu/omap-iommu.c:iopte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3231477040,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/iommu/rockchip-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231491832,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/iommu/exynos-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/exynos-iommu.c:exynos_iommu_map",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3232440472,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 3232553772,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3232592184,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/net/ethernet/ti/davinci_cpdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si"
      ],
      "caller_func": []
    },
    {
      "addr": 3232716716,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 3232841580,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 3232890160,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 3233098792,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 3233144220,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3233234316,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/gadget/udc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3233392968,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/i2c/busses/i2c-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 3233727796,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 3233958936,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:sdhci_setup_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3234030104,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/qcom_scm-32.c:qcom_scm_call"
      ],
      "caller_func": []
    },
    {
      "addr": 3234085136,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/firmware/tegra/ivc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234185708,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/staging/emxx_udc/emxx_udc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234212628,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 3235231656,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 3235639996,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3236267500,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285931836,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285982388,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286210240,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289519332,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289956840,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291264452,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291390764,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291814876,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292031232,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/char/tpm/tpm_ibmvtpm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe",
        "drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293213888,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293533368,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293707532,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293785184,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294059436,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294122244,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294750304,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295120728,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296093352,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296627376,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297439496,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272512316,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272640864,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272672474,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272782208,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274653212,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274924674,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275815414,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275943190,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276190274,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276990366,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277157248,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277272590,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277325456,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277504000,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277546750,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277918114,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278051514,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/mmc/host/mmc_spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278691672,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279033910,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279570390,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_set_status",
        "net/packet/af_packet.c:__packet_set_status",
        "net/packet/af_packet.c:__packet_set_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579069415,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579365764,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039493,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194437,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227747,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393175,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583640406,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583927653,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584837555,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585264169,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585619829,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586683029,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586864276,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586984545,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587024483,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587205578,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587610630,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587842581,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588533648,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588920516,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504168,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579002135,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296103,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580986773,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141189,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174419,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335751,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577462,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583864597,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584767379,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585216585,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585484885,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586101385,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/nvdimm/pmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pmem.c:pmem_do_bvec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551365,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586808260,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586964330,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587008974,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587378646,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587564037,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/hv/channel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel.c:virt_to_hvpfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588245648,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588632452,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589230232,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579068999,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579365684,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030693,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581185637,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581218947,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384375,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583624182,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583911413,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584838979,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585452489,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585809221,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586880565,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587112756,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587233025,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587272963,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587454106,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587498750,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663720,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/i2c/busses/i2c-amd-mp2-plat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935798,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588865824,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907235,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netfilter/nfnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nfnetlink.c:nfnetlink_rcv_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589356900,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589945432,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_vmalloc_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579072839,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579374116,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092133,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248885,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282371,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:per_cpu_ptr_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448695,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show",
        "mm/vmalloc.c:is_vmalloc_or_module_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722246,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "security/apparmor/match.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012709,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944051,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585560665,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585916885,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586986693,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587222660,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587339793,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587379731,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587561424,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587606478,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588051062,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303221,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589007312,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589399524,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589997768,
      "name": "is_vmalloc_addr",
      "external": false,
      "loc": "include/linux/mm.h:643",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:free_pg_vec",
        "net/packet/af_packet.c:tpacket_snd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool is_vmalloc_addr(const void * x)
```
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
