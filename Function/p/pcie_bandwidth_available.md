# Function: <code>pcie_bandwidth_available</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192032,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5215",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192032,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584280704,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5503",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280704,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584475120,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5597",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475120,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584610640,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5727",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584610640,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288192,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5757",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288192,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585442864,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5831",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585442864,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585323024,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5880",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323024,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585779424,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:6070",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779424,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586967216,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:6166",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586967216,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588131600,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:6113",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588131600,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588406544,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:6235",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406544,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701728,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:6380",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701728,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496849976,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5727",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496849976,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230130392,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5727",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230130392,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290928208,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5727",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290928208,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275553920,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5727",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275553920,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584562800,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5727",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562800,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584490960,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5727",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584490960,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584560800,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5727",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560800,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
```

```json
{
  "name": "pcie_bandwidth_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668544,
      "name": "pcie_bandwidth_available",
      "external": true,
      "loc": "drivers/pci/pci.c:5727",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668544,
      "name": "pcie_bandwidth_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
u32 pcie_bandwidth_available(struct pci_dev * dev, struct pci_dev * * limiting_dev, enum pci_bus_speed * speed, enum pcie_link_width * width)
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
