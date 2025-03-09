# Function: <code>pci_bus_restore_locked</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584494128,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5179",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584494128,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584629744,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629744,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585312672,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5339",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311792,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585462592,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5407",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457120,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585342697,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5456",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585337328,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585802169,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5646",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801072,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586990231,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5742",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586989104,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588157431,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5679",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156288,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588432951,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5801",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588431808,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588729607,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5911",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588728464,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496875376,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496875376,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230152760,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230152760,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290958896,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290958896,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275574106,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275574106,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581904,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581904,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584510032,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510032,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584579904,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584579904,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void pci_bus_restore_locked(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_restore_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687616,
      "name": "pci_bus_restore_locked",
      "external": false,
      "loc": "drivers/pci/pci.c:5309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687616,
      "name": "pci_bus_restore_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void pci_bus_restore_locked(struct pci_bus * bus)
```
</details>
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
