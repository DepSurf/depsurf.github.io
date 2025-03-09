# Function: <code>proc_create_single_data</code>

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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124688,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:613",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/rtc-proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124688,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219152,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:615",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219152,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383360,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383360,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582482272,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482272,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582781040,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:629",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/bootconfig.c:proc_boot_config_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/connector/connector.c:cn_init",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582781040,
      "name": "proc_create_single_data",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582854496,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:649",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/bootconfig.c:proc_boot_config_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/connector/connector.c:cn_init",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854496,
      "name": "proc_create_single_data",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582882800,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/bootconfig.c:proc_boot_config_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882800,
      "name": "proc_create_single_data",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583216416,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/bootconfig.c:proc_boot_config_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216416,
      "name": "proc_create_single_data",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583713760,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:647",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/bootconfig.c:proc_boot_config_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713760,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584325344,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:647",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/bootconfig.c:proc_boot_config_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325344,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584555392,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:646",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/bootconfig.c:proc_boot_config_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555392,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787248,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:646",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/proc/bootconfig.c:proc_boot_config_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/connector/connector.c:cn_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv4/route.c:ip_rt_do_proc_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787248,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494104208,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494104208,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227553848,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/swp_emulate.c:swp_emulation_init",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/mtd/mtdcore.c:init_mtd",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227553848,
      "name": "proc_create_single_data",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287772624,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtas-proc.c:proc_rtas_init",
        "arch/powerpc/kernel/rtas-proc.c:proc_rtas_init",
        "arch/powerpc/kernel/eeh.c:eeh_init_proc",
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287772624,
      "name": "proc_create_single_data",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273590472,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273590472,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451008,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451008,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388176,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388176,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441488,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441488,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_single_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521664,
      "name": "proc_create_single_data",
      "external": true,
      "loc": "fs/proc/generic.c:616",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exec_domain.c:proc_execdomains_init",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/dma.c:proc_dma_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "fs/filesystems.c:proc_filesystems_init",
        "fs/proc/proc_tty.c:proc_tty_register_driver",
        "fs/proc/cmdline.c:proc_cmdline_init",
        "fs/proc/loadavg.c:proc_loadavg_init",
        "fs/proc/meminfo.c:proc_meminfo_init",
        "fs/proc/uptime.c:proc_uptime_init",
        "fs/proc/version.c:proc_version_init",
        "fs/proc/softirqs.c:proc_softirqs_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/rtc/proc.c:rtc_proc_add_device",
        "net/sched/sch_api.c:psched_net_init",
        "net/ipv6/proc.c:snmp6_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521664,
      "name": "proc_create_single_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct proc_dir_entry * proc_create_single_data(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
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
