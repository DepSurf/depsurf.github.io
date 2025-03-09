# Function: <code>pcibios_add_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586162144,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "arch/x86/pci/common.c:174",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162144,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586575344,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2121",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_add_new_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586575344,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586756896,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2271",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756896,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583728912,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2397",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586883728,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583987008,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2624",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587372384,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584181120,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2808",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587676208,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584269792,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2934",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807504,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584460672,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3160",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588112992,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596016,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2894",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318688,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585273632,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2946",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139056,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585432240,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2953",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223264,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585312464,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2997",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591172512,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585768352,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3039",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592026032,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586953984,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3010",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593792960,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588116048,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3020",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595735968,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588391136,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3034",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596261952,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588687072,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3083",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597144560,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490319552,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "arch/arm64/kernel/pci.c:210",
      "file": "arch/arm64/kernel/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490319552,
      "name": "pcibios_add_bus",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230118632,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2894",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230118632,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290912960,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2894",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290912960,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 12
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275543644,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2894",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275543644,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 26
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584548176,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2894",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922336,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476336,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2894",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587638304,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584546176,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2894",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255744,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pcibios_add_bus(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_add_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584653920,
      "name": "pcibios_add_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2894",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588391264,
      "name": "pcibios_add_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
