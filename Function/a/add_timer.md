# Function: <code>add_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579821216,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:964",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_reseed",
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/video/console/fbcon.c:fbcon_add_cursor_timer",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "net/core/flow.c:flow_cache_new_hashrnd",
        "net/core/flow.c:flow_cache_init",
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821216,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579849216,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1104",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout",
        "drivers/video/console/fbcon.c:fbcon_add_cursor_timer",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/flow.c:flow_cache_init",
        "net/core/flow.c:flow_cache_new_hashrnd",
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849216,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579878064,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1114",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout",
        "drivers/video/console/fbcon.c:fbcon_add_cursor_timer",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/flow.c:flow_cache_init",
        "net/core/flow.c:flow_cache_new_hashrnd",
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878064,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579887424,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1089",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/flow.c:flow_cache_init",
        "net/core/flow.c:flow_cache_new_hashrnd",
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887424,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579931680,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1127",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931680,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579977456,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1135",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977456,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580022064,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1134",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022064,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580065984,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1129",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065984,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580115040,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1133",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115040,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580174832,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1145",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:jbd2_get_transaction",
        "block/blk-iocost.c:ioc_start_period",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_qc_schedule_eh",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_init",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174832,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580163504,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1139",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:jbd2_get_transaction",
        "block/blk-iocost.c:ioc_start_period",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_qc_schedule_eh",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_init",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163504,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580167088,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1141",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:jbd2_get_transaction",
        "block/blk-iocost.c:ioc_start_period",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_end_foreign_access",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_qc_schedule_eh",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_init",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167088,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311792,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1141",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:start_sync_check_timer",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-iocost.c:ioc_start_period",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_init",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311792,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580523632,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1194",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:start_sync_check_timer",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-iocost.c:ioc_start_period",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_init",
        "net/core/drop_monitor.c:net_dm_hw_trap_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523632,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779248,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1240",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:start_sync_check_timer",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-iocost.c:ioc_start_period",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_init",
        "net/core/drop_monitor.c:net_dm_hw_trap_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779248,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862240,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1240",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:start_sync_check_timer",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/rcu/update.c:tasks_rcu_exit_srcu_stall",
        "kernel/rcu/update.c:rcu_tasks_postscan",
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-iocost.c:ioc_start_period",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_init",
        "net/core/drop_monitor.c:net_dm_hw_trap_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862240,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952384,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1240",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:start_sync_check_timer",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/rcu/update.c:tasks_rcu_exit_srcu_stall",
        "kernel/rcu/update.c:rcu_tasks_postscan",
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-iocost.c:ioc_start_period",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_init",
        "net/core/drop_monitor.c:net_dm_hw_trap_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952384,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491334576,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1133",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491334576,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225324956,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1133",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "block/blk-iocost.c:ioc_start_period",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_start",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_timer",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225324956,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284259616,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1133",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284259616,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271831296,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1133",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271831296,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580084240,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1133",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084240,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580029584,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1133",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029584,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580075312,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1133",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/netfilter/nfnetlink_log.c:nfulnl_log_packet",
        "net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_expect",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075312,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void add_timer(struct timer_list * timer)
```

```json
{
  "name": "add_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580129328,
      "name": "add_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1133",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/pstore/platform.c:pstore_register",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:__prandom_timer",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout",
        "drivers/acpi/apei/ghes.c:ghes_add_timer",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/ipv4/igmp.c:igmp_heard_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129328,
      "name": "add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
