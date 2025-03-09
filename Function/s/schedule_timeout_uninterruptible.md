# Function: <code>schedule_timeout_uninterruptible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587378704,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1562",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/tree.c:synchronize_sched_expedited",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/swapfile.c:SyS_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587378704,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579843978,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1778",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:SyS_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587881568,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579873082,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1783",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:SyS_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098272,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579885397,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1774",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:SyS_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588323920,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579928580,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1824",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:SYSC_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890000,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579974372,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1835",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589268256,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580025668,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1834",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589510816,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580068929,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1838",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589970016,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580117985,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197680,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580174913,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1947",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_gp_init",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "net/sched/sch_generic.c:dev_deactivate_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591213360,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580163585,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1909",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "net/sched/sch_generic.c:dev_deactivate_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591708592,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580167169,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "net/sched/sch_generic.c:dev_deactivate_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591655968,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580311985,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1912",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "net/sched/sch_generic.c:dev_deactivate_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592829632,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580523825,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1966",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "net/sched/sch_generic.c:dev_deactivate_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594738432,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580779489,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:2198",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "net/sched/sch_generic.c:dev_deactivate_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596490544,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580862481,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:2198",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "net/sched/sch_generic.c:dev_deactivate_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597031856,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580952625,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:2214",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "net/sched/sch_generic.c:dev_deactivate_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597961248,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491331880,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503944480,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225325556,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236553384,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284260448,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297797392,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271833814,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279808386,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580087185,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589799968,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580032529,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589522416,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580078257,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590243376,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int schedule_timeout_uninterruptible(long int timeout)
```

```json
{
  "name": "schedule_timeout_uninterruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580126785,
      "name": "schedule_timeout_uninterruptible",
      "external": true,
      "loc": "kernel/time/timer.c:1926",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep"
      ],
      "caller_func": [
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590293696,
      "name": "schedule_timeout_uninterruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
