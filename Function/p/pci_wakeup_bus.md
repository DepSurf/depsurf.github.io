# Function: <code>pci_wakeup_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583262396,
      "name": "pci_wakeup_bus",
      "external": false,
      "loc": "drivers/pci/pci.c:761",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583572399,
      "name": "pci_wakeup_bus",
      "external": false,
      "loc": "drivers/pci/pci.c:782",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583708991,
      "name": "pci_wakeup_bus",
      "external": false,
      "loc": "drivers/pci/pci.c:807",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583750031,
      "name": "pci_wakeup_bus",
      "external": false,
      "loc": "drivers/pci/pci.c:802",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584009055,
      "name": "pci_wakeup_bus",
      "external": false,
      "loc": "drivers/pci/pci.c:803",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584204591,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:815",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205680,
      "name": "pci_wakeup_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584292895,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:986",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293488,
      "name": "pci_wakeup_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584487100,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:1012",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487744,
      "name": "pci_wakeup_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584623365,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:999",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584623248,
      "name": "pci_wakeup_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585304925,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:1053",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306160,
      "name": "pci_wakeup_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496867224,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:999",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496867048,
      "name": "pci_wakeup_bus",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230145172,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:999",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230145016,
      "name": "pci_wakeup_bus",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290948556,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:999",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290948336,
      "name": "pci_wakeup_bus",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275566948,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:999",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275566786,
      "name": "pci_wakeup_bus",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584575525,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:999",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584575408,
      "name": "pci_wakeup_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584503685,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:999",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503568,
      "name": "pci_wakeup_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584573525,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:999",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573408,
      "name": "pci_wakeup_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_wakeup_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_wakeup_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584681269,
      "name": "pci_wakeup_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:999",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681152,
      "name": "pci_wakeup_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_wakeup_bus(struct pci_bus * bus)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void pci_wakeup_bus(struct pci_bus * bus)
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
