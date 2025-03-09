# Function: <code>pci_dev_reset_slot_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583269990,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:3590",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583580442,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:3911",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583717498,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:3949",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583742144,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4067",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742144,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000464,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4104",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000464,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194160,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4353",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194160,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584283648,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4644",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283648,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478176,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4741",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478176,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613664,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613664,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585290816,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4901",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290816,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585471658,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4975",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585351578,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:5024",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_probe_reset_function"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585809685,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:5076",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586998597,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:5172",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588166981,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:5109",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
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
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588443173,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:5231",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
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
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588740037,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:5341",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496852904,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496852904,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230133880,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230133880,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290932608,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290932608,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275556516,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275556516,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584565824,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565824,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584493984,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584493984,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584563824,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563824,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_dev_reset_slot_function",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584671568,
      "name": "pci_dev_reset_slot_function",
      "external": false,
      "loc": "drivers/pci/pci.c:4871",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584671568,
      "name": "pci_dev_reset_slot_function",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev * dev, int probe)
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
