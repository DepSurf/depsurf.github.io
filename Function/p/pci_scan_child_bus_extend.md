# Function: <code>pci_scan_child_bus_extend</code>

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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583991728,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2491",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991728,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584185744,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2649",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185744,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584274448,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2775",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584274448,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584464784,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:3001",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464784,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584600160,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2735",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600160,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585277520,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2787",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585277520,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585436224,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2794",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436224,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585316352,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2838",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316352,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585772240,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2880",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772240,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586958000,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2866",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586958000,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588121120,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2878",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121120,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588396384,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2892",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588396384,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588692368,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2941",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588692368,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496842608,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2735",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496842608,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230123220,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2735",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230123220,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290918640,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2735",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290918640,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275547428,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2735",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275547428,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 786
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584552320,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2735",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552320,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584480480,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2735",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480480,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584550320,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2735",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584550320,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
```

```json
{
  "name": "pci_scan_child_bus_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584658064,
      "name": "pci_scan_child_bus_extend",
      "external": false,
      "loc": "drivers/pci/probe.c:2735",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_rescan_bus",
        "drivers/pci/probe.c:pci_rescan_bus_bridge_resize",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658064,
      "name": "pci_scan_child_bus_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
unsigned int pci_scan_child_bus_extend(struct pci_bus * bus, unsigned int available_buses)
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
