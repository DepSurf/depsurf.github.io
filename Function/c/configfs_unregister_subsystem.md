# Function: <code>configfs_unregister_subsystem</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858960,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1891",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858960,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008848,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1891",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008848,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1902",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202192,
      "name": "configfs_unregister_subsystem.cold.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582195936,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1902",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297312,
      "name": "configfs_unregister_subsystem.cold.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582291152,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1962",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463490,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582458048,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1919",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562703,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582557904,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1920",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870607,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582866032,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1921",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346579,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582938976,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1920",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591289329,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582966064,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1907",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592249288,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583299904,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1907",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594030355,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583809200,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584430512,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1909",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584430512,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659264,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1904",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659264,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584892016,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1904",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892016,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494197936,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1919",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494197936,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227633796,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1919",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227633796,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287891664,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1919",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287891664,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273659314,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1919",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273659314,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1919",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531439,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582526640,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1919",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468607,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582463808,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1919",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521919,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582517120,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
```

```json
{
  "name": "configfs_unregister_subsystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_unregister_subsystem",
      "external": true,
      "loc": "fs/configfs/dir.c:1919",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602607,
      "name": "configfs_unregister_subsystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582597696,
      "name": "configfs_unregister_subsystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void configfs_unregister_subsystem(struct configfs_subsystem * subsys)
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
