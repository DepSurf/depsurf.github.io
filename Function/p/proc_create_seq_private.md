# Function: <code>proc_create_seq_private</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124592,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:583",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124592,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219056,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:585",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219056,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383264,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383264,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582482176,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482176,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582780944,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:598",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780944,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582854400,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:618",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854400,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582882704,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:613",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882704,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583216320,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:613",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216320,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583713648,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/build_utility.c:proc_schedstat_init",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713648,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584325216,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/build_utility.c:proc_schedstat_init",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325216,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584555264,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:615",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/build_utility.c:proc_schedstat_init",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555264,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787120,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:615",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/build_utility.c:proc_schedstat_init",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fb_procfs.c:fb_init_procfs",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv4/route.c:ip_rt_do_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787120,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494104064,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494104064,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227553752,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227553752,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287772496,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287772496,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273590356,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273590356,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450912,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450912,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388080,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388080,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441392,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441392,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_seq_private",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521568,
      "name": "proc_create_seq_private",
      "external": true,
      "loc": "fs/proc/generic.c:586",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:ioresources_init",
        "kernel/resource.c:ioresources_init",
        "kernel/sched/stats.c:proc_schedstat_init",
        "kernel/sched/debug.c:init_sched_debug_procfs",
        "kernel/time/timer_list.c:init_timer_list_procfs",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmalloc.c:proc_vmalloc_init",
        "fs/locks.c:proc_locks_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/consoles.c:proc_consoles_init",
        "fs/proc/devices.c:proc_devices_init",
        "fs/proc/interrupts.c:proc_interrupts_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "security/keys/proc.c:key_proc_init",
        "security/keys/proc.c:key_proc_init",
        "crypto/proc.c:crypto_init_proc",
        "block/genhd.c:proc_genhd_init",
        "block/genhd.c:proc_genhd_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/misc.c:misc_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/net-procfs.c:dev_proc_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521568,
      "name": "proc_create_seq_private",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct proc_dir_entry * proc_create_seq_private(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```
</details>
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
