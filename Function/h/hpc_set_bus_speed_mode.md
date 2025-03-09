# Function: <code>hpc_set_bus_speed_mode</code>

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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584344864,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344864,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584440048,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440048,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584636352,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584637702,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774048,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584775398,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585465456,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071585467039,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585610000,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071591416777,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:701",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585488448,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071591358904,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:701",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585955328,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071592387420,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:701",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159808,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071594251297,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588369664,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:684",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369664,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588645664,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:684",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588645664,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588946064,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:684",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588946064,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497037456,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497037456,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275695998,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275695998,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584722864,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584724214,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653632,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584654982,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724208,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584725558,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```

```json
{
  "name": "hpc_set_bus_speed_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpc_set_bus_speed_mode",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:706",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584831776,
      "name": "hpc_set_bus_speed_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584833126,
      "name": "hpc_set_bus_speed_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int hpc_set_bus_speed_mode(struct slot * slot, enum pci_bus_speed value)
```
</details>
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
