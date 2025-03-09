# Function: <code>pci_bridge_d3_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev * dev, bool remove)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583568400,
      "name": "pci_bridge_d3_update",
      "external": false,
      "loc": "drivers/pci/pci.c:2244",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_d3_device_removed",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568400,
      "name": "pci_bridge_d3_update",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712576,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2297",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712576,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583753728,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2314",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583753728,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012752,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2323",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012752,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208384,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2398",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208384,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296256,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2588",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296256,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584490672,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2703",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584490672,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584626256,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2699",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626256,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585309072,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585309072,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585465840,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2936",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585465840,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346080,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346080,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:3008",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592364239,
      "name": "pci_bridge_d3_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585805232,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:3095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594226484,
      "name": "pci_bridge_d3_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586993616,
      "name": "pci_bridge_d3_update",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:3045",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596208660,
      "name": "pci_bridge_d3_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071588161216,
      "name": "pci_bridge_d3_update",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:3083",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596733818,
      "name": "pci_bridge_d3_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071588436736,
      "name": "pci_bridge_d3_update",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:3196",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci-sysfs.c:d3cold_allowed_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597642241,
      "name": "pci_bridge_d3_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071588733568,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496870936,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2699",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496870936,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230148368,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2699",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230148368,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290953136,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2699",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290953136,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275569946,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2699",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275569946,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584578416,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2699",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578416,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584506544,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2699",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584506544,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584576416,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2699",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584576416,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void pci_bridge_d3_update(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_d3_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584684128,
      "name": "pci_bridge_d3_update",
      "external": true,
      "loc": "drivers/pci/pci.c:2699",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/pci.c:pci_d3cold_disable",
        "drivers/pci/pci.c:pci_d3cold_enable",
        "drivers/pci/pci.c:pci_bridge_d3_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684128,
      "name": "pci_bridge_d3_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void pci_bridge_d3_update(struct pci_dev * dev, bool remove)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool remove</code>
</li>
</ul>
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
