# Function: <code>pci_scan_bridge_extend</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583990080,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:986",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990080,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1606
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584184224,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1057",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184224,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1478
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584272928,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1057",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584272928,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1144",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463216,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1536
    },
    {
      "addr": 18446744071584470722,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1146",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598560,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
    },
    {
      "addr": 18446744071584606006,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1194",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585275824,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1662
    },
    {
      "addr": 18446744071585283149,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1213",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434528,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1657
    },
    {
      "addr": 18446744071591393637,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1256",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314656,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1659
    },
    {
      "addr": 18446744071591335947,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1265",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585770544,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1659
    },
    {
      "addr": 18446744071592362417,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1246",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586956240,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1699
    },
    {
      "addr": 18446744071594224577,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588119216,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1251",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588119216,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1811
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394368,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1254",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394368,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1921
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588690352,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1265",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588690352,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1921
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496841080,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1146",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496841080,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1448
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230121504,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1146",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230121504,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1668
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290916656,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1146",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290916656,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1952
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
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275546210,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1146",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275546210,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1150
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1146",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584550720,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
    },
    {
      "addr": 18446744071584558166,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1146",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478880,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
    },
    {
      "addr": 18446744071584486326,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1146",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548720,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
    },
    {
      "addr": 18446744071584556166,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```

```json
{
  "name": "pci_scan_bridge_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_bridge_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:1146",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_child_bus_extend",
        "drivers/pci/probe.c:pci_scan_child_bus_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584656464,
      "name": "pci_scan_bridge_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
    },
    {
      "addr": 18446744071584663910,
      "name": "pci_scan_bridge_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int pci_scan_bridge_extend(struct pci_bus * bus, struct pci_dev * dev, int max, unsigned int available_buses, int pass)
```
</details>
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
