# Function: <code>mp_map_pin_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202704,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1028",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202704,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203392,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1029",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203392,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579215056,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1028",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215056,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212544,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1028",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212544,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579230192,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1030",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230192,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579242544,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1031",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579242544,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579266320,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1031",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266320,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579280592,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1034",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579280592,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283056,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1034",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283056,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579312720,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1021",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312720,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579318064,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1020",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318064,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320832,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1020",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320832,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 787
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1020",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369328,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1049
    },
    {
      "addr": 18446744071592075315,
      "name": "mp_map_pin_to_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1021",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433040,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1117
    },
    {
      "addr": 18446744071593841907,
      "name": "mp_map_pin_to_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1021",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517824,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1163
    },
    {
      "addr": 18446744071595965747,
      "name": "mp_map_pin_to_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1022",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530304,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1188
    },
    {
      "addr": 18446744071596483413,
      "name": "mp_map_pin_to_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1022",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559072,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1188
    },
    {
      "addr": 18446744071597379699,
      "name": "mp_map_pin_to_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579281760,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1034",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281760,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579217088,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1034",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217088,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579282960,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1034",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282960,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```

```json
{
  "name": "mp_map_pin_to_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288848,
      "name": "mp_map_pin_to_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:1034",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:pin_2_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288848,
      "name": "mp_map_pin_to_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info * info)
```
</details>
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
