# Function: <code>pci_bus_set_current_state</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584204354,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:869",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205712,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584292658,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1040",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293520,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584486850,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1066",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487776,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584622450,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1051",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584623280,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585305078,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1143",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306272,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585461318,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1277",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462896,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585341204,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1307",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343008,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585798196,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1317",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585799408,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586986172,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1337",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586987280,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588153117,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1318",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588154336,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588428716,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1356",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588429856,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726512,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1426",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726512,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496866124,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1051",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496867112,
      "name": "pci_bus_set_current_state",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230144112,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1051",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230145064,
      "name": "pci_bus_set_current_state",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290946980,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1051",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290948416,
      "name": "pci_bus_set_current_state",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275566068,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1051",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275566840,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584574610,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1051",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584575440,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584502770,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1051",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503600,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584572610,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1051",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573440,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
```

```json
{
  "name": "pci_bus_set_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584680354,
      "name": "pci_bus_set_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1051",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681184,
      "name": "pci_bus_set_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_bus_set_current_state(struct pci_bus * bus, pci_power_t state)
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
