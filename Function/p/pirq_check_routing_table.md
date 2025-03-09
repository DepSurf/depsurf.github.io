# Function: <code>pirq_check_routing_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586164352,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:64",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586164352,
      "name": "pirq_check_routing_table.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595521662,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:64",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577631,
      "name": "pirq_check_routing_table.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595777721,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:64",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759141,
      "name": "pirq_check_routing_table.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586882579,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:64",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586882579,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587371235,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587371235,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587674931,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587674931,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587806227,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806227,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588111219,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588111219,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588316915,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588316915,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591137267,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591137267,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591642898,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591642898,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591586542,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591586542,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592757643,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:71",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592757643,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr, u8 * limit)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594645658,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:73",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pirq_find_routing_table",
        "arch/x86/pci/irq.c:pirq_find_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594645658,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628218801,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:73",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_find_routing_table",
        "arch/x86/pci/irq.c:pirq_find_routing_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619987697,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:73",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_find_routing_table",
        "arch/x86/pci/irq.c:pirq_find_routing_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622300303,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:73",
      "file": "arch/x86/pci/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/irq.c:pirq_find_routing_table",
        "arch/x86/pci/irq.c:pirq_find_routing_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587920563,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587920563,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587636691,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587636691,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588253971,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588253971,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```

```json
{
  "name": "pirq_check_routing_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588389395,
      "name": "pirq_check_routing_table",
      "external": false,
      "loc": "arch/x86/pci/irq.c:65",
      "file": "arch/x86/pci/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/irq.c:pcibios_irq_init",
        "arch/x86/pci/irq.c:pcibios_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588389395,
      "name": "pirq_check_routing_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```
</details>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 * limit</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct irq_routing_table * pirq_check_routing_table(u8 * addr, u8 * limit)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct irq_routing_table * pirq_check_routing_table(u8 * addr)
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
