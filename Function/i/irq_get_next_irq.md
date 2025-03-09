# Function: <code>irq_get_next_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738896,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:532",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738896,
      "name": "irq_get_next_irq",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760656,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:593",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760656,
      "name": "irq_get_next_irq",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787504,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:781",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787504,
      "name": "irq_get_next_irq",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579785024,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:798",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785024,
      "name": "irq_get_next_irq",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818496,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:787",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818496,
      "name": "irq_get_next_irq",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852352,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:804",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852352,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899344,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:809",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899344,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934160,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934160,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984288,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984288,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032592,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_all_irqs",
        "fs/proc/stat.c:show_all_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032592,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016336,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:821",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_all_irqs",
        "fs/proc/stat.c:show_all_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016336,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016992,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:821",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016992,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149216,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:833",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149216,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294000,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:810",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294000,
      "name": "irq_get_next_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580504896,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:837",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504896,
      "name": "irq_get_next_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576976,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:856",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576976,
      "name": "irq_get_next_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641264,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:856",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641264,
      "name": "irq_get_next_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491171120,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491171120,
      "name": "irq_get_next_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225196276,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225196276,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284070256,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284070256,
      "name": "irq_get_next_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271722908,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271722908,
      "name": "irq_get_next_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953024,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953024,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890896,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890896,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944560,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944560,
      "name": "irq_get_next_irq",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset)
```

```json
{
  "name": "irq_get_next_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990912,
      "name": "irq_get_next_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:864",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990912,
      "name": "irq_get_next_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
