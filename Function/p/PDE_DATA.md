# Function: <code>PDE_DATA</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581461552,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:irq_spurious_proc_open",
        "kernel/irq/proc.c:irq_node_proc_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_hint_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "kernel/irq/proc.c:default_affinity_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/ext4/sysfs.c:es_shrinker_info_open",
        "fs/ext4/sysfs.c:options_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/acpi/button.c:acpi_button_state_open_fs",
        "drivers/tty/serial/serial_core.c:uart_proc_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "drivers/rtc/rtc-proc.c:rtc_proc_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv6/proc.c:snmp6_dev_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461552,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581645904,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:649",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:irq_spurious_proc_open",
        "kernel/irq/proc.c:irq_node_proc_open",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_hint_proc_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/ext4/sysfs.c:options_open",
        "fs/ext4/sysfs.c:es_shrinker_info_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/acpi/button.c:acpi_button_state_open_fs",
        "drivers/tty/serial/serial_core.c:uart_proc_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "drivers/rtc/rtc-proc.c:rtc_proc_release",
        "drivers/rtc/rtc-proc.c:rtc_proc_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv6/proc.c:snmp6_dev_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645904,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581734176,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:651",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:irq_spurious_proc_open",
        "kernel/irq/proc.c:irq_node_proc_open",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_hint_proc_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/ext4/sysfs.c:options_open",
        "fs/ext4/sysfs.c:es_shrinker_info_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/acpi/button.c:acpi_button_state_open_fs",
        "drivers/tty/serial/serial_core.c:uart_proc_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "drivers/rtc/rtc-proc.c:rtc_proc_release",
        "drivers/rtc/rtc-proc.c:rtc_proc_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv6/proc.c:snmp6_dev_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734176,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788352,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:635",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:irq_spurious_proc_open",
        "kernel/irq/proc.c:irq_node_proc_open",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_open",
        "kernel/irq/proc.c:irq_effective_aff_proc_open",
        "kernel/irq/proc.c:irq_affinity_hint_proc_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/ext4/sysfs.c:options_open",
        "fs/ext4/sysfs.c:es_shrinker_info_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/acpi/button.c:acpi_button_state_open_fs",
        "drivers/tty/serial/serial_core.c:uart_proc_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "drivers/rtc/rtc-proc.c:rtc_proc_release",
        "drivers/rtc/rtc-proc.c:rtc_proc_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv6/proc.c:snmp6_dev_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788352,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581937808,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:645",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:irq_spurious_proc_open",
        "kernel/irq/proc.c:irq_node_proc_open",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_open",
        "kernel/irq/proc.c:irq_effective_aff_proc_open",
        "kernel/irq/proc.c:irq_affinity_hint_proc_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/ext4/sysfs.c:options_open",
        "fs/ext4/sysfs.c:es_shrinker_info_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/acpi/button.c:acpi_button_state_open_fs",
        "drivers/tty/serial/serial_core.c:uart_proc_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "drivers/rtc/rtc-proc.c:rtc_proc_release",
        "drivers/rtc/rtc-proc.c:rtc_proc_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv6/proc.c:snmp6_dev_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937808,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582121888,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:747",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121888,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582216320,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:749",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216320,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582380464,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582380464,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582479376,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582479376,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582777712,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:779",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/tcp_ipv4.c:established_get_first",
        "net/ipv4/tcp_ipv4.c:listening_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next",
        "net/ipv4/udp.c:udp_get_first"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777712,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582851040,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:799",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582851040,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582879424,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:794",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop",
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_start",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879424,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213040,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:794",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop",
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_start",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/tcp_ipv4.c:established_get_first",
        "net/ipv4/tcp_ipv4.c:listening_get_next",
        "net/ipv4/tcp_ipv4.c:listening_get_first",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213040,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494100336,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494100336,
      "name": "PDE_DATA",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227550580,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/atags_proc.c:atags_read",
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "sound/core/info.c:snd_info_text_entry_open",
        "sound/core/info.c:snd_info_entry_open",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/tcp_ipv4.c:established_get_first",
        "net/ipv4/tcp_ipv4.c:listening_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next",
        "net/ipv4/udp.c:udp_get_first"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227550580,
      "name": "PDE_DATA",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287768160,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/proc_powerpc.c:page_map_mmap",
        "arch/powerpc/kernel/proc_powerpc.c:page_map_read",
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/tcp_ipv4.c:established_get_first",
        "net/ipv4/tcp_ipv4.c:listening_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next",
        "net/ipv4/udp.c:udp_get_first"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287768160,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273585950,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/tcp_ipv4.c:established_get_first",
        "net/ipv4/tcp_ipv4.c:listening_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next",
        "net/ipv4/udp.c:udp_get_first"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273585950,
      "name": "PDE_DATA",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448112,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448112,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582385280,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385280,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438592,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438592,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * PDE_DATA(const struct inode * inode)
```

```json
{
  "name": "PDE_DATA",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518768,
      "name": "PDE_DATA",
      "external": true,
      "loc": "fs/proc/generic.c:750",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:r_show",
        "kernel/resource.c:r_start",
        "kernel/irq/proc.c:default_affinity_open",
        "kernel/irq/proc.c:irq_affinity_list_proc_open",
        "kernel/irq/proc.c:irq_affinity_proc_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_next",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_start",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "ipc/util.c:sysvipc_proc_open",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_lseek",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_host_write",
        "net/core/neighbour.c:neigh_stat_seq_show",
        "net/core/neighbour.c:neigh_stat_seq_next",
        "net/core/neighbour.c:neigh_stat_seq_start",
        "net/ipv4/tcp_ipv4.c:established_get_next",
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_seq_start",
        "net/ipv4/raw.c:raw_get_next",
        "net/ipv4/raw.c:raw_get_first",
        "net/ipv4/udp.c:udp_seq_stop",
        "net/ipv4/udp.c:udp_get_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518768,
      "name": "PDE_DATA",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void * PDE_DATA(const struct inode * inode)
```
</details>
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
