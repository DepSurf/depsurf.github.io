# Function: <code>proc_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465600,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:637",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465600,
      "name": "proc_remove",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650000,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:642",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650000,
      "name": "proc_remove",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738304,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738304,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581792208,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:628",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792208,
      "name": "proc_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581941552,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:638",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941552,
      "name": "proc_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582126080,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:740",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126080,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582220560,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:742",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582220560,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582384784,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384784,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582483696,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483696,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582782944,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:772",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782944,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582856400,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:792",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856400,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582884608,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:787",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884608,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583218224,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:787",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218224,
      "name": "proc_remove",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583715808,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:790",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715808,
      "name": "proc_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584327504,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:790",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584327504,
      "name": "proc_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584557616,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:789",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557616,
      "name": "proc_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584789472,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:789",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "drivers/video/fbdev/core/fb_procfs.c:fb_cleanup_procfs",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789472,
      "name": "proc_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494106344,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494106344,
      "name": "proc_remove",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227555584,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "sound/core/info.c:snd_info_disconnect",
        "sound/core/info.c:snd_info_card_disconnect",
        "sound/core/info.c:snd_info_card_id_change",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227555584,
      "name": "proc_remove",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287774880,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287774880,
      "name": "proc_remove",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273588208,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273588208,
      "name": "proc_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582452432,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452432,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582389600,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582389600,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582442912,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442912,
      "name": "proc_remove",
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
void proc_remove(struct proc_dir_entry * de)
```

```json
{
  "name": "proc_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582523120,
      "name": "proc_remove",
      "external": true,
      "loc": "fs/proc/generic.c:743",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:unregister_handler_proc",
        "fs/proc/vmcore.c:vmcore_cleanup",
        "drivers/pci/proc.c:pci_proc_detach_bus",
        "drivers/pci/proc.c:pci_proc_detach_device",
        "net/ipv6/proc.c:snmp6_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582523120,
      "name": "proc_remove",
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
