# Function: <code>proc_mkdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463680,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:458",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "fs/jbd2/journal.c:journal_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463680,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648064,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:462",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648064,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736368,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:464",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736368,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790224,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:447",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790224,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939552,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:449",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939552,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124160,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:488",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124160,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218624,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:490",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218624,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582382848,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382848,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481760,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481760,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582780448,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:500",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/input/input.c:input_init",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780448,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582853760,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:520",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/acpi/button.c:acpi_button_add_fs",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/input/input.c:input_init",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582853760,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582882064,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:515",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882064,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215680,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:515",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215680,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712944,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:518",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_setup_proc_files",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712944,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584324432,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:518",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584324432,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584554480,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:517",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554480,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786336,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:517",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/sched/build_utility.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "ipc/util.c:ipc_init",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786336,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494103456,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494103456,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227553204,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/setup.c:proc_cpu_init",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init",
        "sound/core/info.c:snd_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227553204,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287771872,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/proc_powerpc.c:proc_ppc64_create",
        "arch/powerpc/kernel/proc_powerpc.c:proc_ppc64_create",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287771872,
      "name": "proc_mkdir",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273589892,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273589892,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450496,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450496,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582387664,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387664,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440976,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440976,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct proc_dir_entry * proc_mkdir(const char * name, struct proc_dir_entry * parent)
```

```json
{
  "name": "proc_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521152,
      "name": "proc_mkdir",
      "external": true,
      "loc": "fs/proc/generic.c:491",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/sched/psi.c:psi_proc_init",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/root.c:proc_root_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_tty.c:proc_tty_init",
        "fs/proc/proc_sysctl.c:proc_sys_init",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_stats_proc_init",
        "ipc/util.c:ipc_init",
        "drivers/pci/proc.c:pci_proc_init",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/scsi/scsi_proc.c:scsi_init_procfs",
        "drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add",
        "drivers/scsi/sg.c:init_sg",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521152,
      "name": "proc_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
