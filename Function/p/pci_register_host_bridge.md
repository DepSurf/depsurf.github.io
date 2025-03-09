# Function: <code>pci_register_host_bridge</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583689808,
      "name": "pci_register_host_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:722",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689808,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1079
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730336,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:749",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730336,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1078
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583988432,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:749",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583988432,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1078
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:773",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584182656,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1054
    },
    {
      "addr": 18446744071584187812,
      "name": "pci_register_host_bridge.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:773",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584271360,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1054
    },
    {
      "addr": 18446744071584276518,
      "name": "pci_register_host_bridge.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:830",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462096,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071584470206,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:826",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597440,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071584605490,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:870",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274608,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071585282587,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:877",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433264,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    },
    {
      "addr": 18446744071591393061,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:895",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585313472,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
    },
    {
      "addr": 18446744071591335243,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:901",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585769360,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
    },
    {
      "addr": 18446744071592361713,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:883",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586955024,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    },
    {
      "addr": 18446744071594223943,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588117280,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:881",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588117280,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1349
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392368,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:881",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392368,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1423
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588688352,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:892",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588688352,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1423
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496839752,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:826",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496839752,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230120156,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:826",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230120156,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290914816,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:826",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290914816,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1220
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275544996,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:826",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275544996,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:826",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584549600,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071584557650,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:826",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477760,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071584485810,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:826",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584547600,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071584555650,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_register_host_bridge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_register_host_bridge",
      "external": false,
      "loc": "drivers/pci/probe.c:826",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_scan_root_bus_bridge",
        "drivers/pci/probe.c:pci_create_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655344,
      "name": "pci_register_host_bridge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071584663394,
      "name": "pci_register_host_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge * bridge)
```
</details>
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
