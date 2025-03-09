# Function: <code>pci_ep_cfs_add_epf_group</code>

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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583896512,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:408",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583896512,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159344,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:411",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159344,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:440",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584379156,
      "name": "pci_ep_cfs_add_epf_group.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584376848,
      "name": "pci_ep_cfs_add_epf_group",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470886,
      "name": "pci_ep_cfs_add_epf_group.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584468624,
      "name": "pci_ep_cfs_add_epf_group",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668226,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584665664,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584806498,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584803936,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:448",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585499308,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585496848,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:448",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591419141,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585629040,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:618",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361585,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585508272,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:642",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592390711,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585975600,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:630",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594255485,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587190016,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588416768,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:630",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588416768,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588693744,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:667",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588693744,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588994464,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:667",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588994464,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497078664,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497078664,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230285532,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230285532,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291117936,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291117936,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275717414,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275717414,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584755234,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584752672,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584686018,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584683456,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756658,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584754096,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
```

```json
{
  "name": "pci_ep_cfs_add_epf_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_ep_cfs_add_epf_group",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-ep-cfs.c:464",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864178,
      "name": "pci_ep_cfs_add_epf_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584861616,
      "name": "pci_ep_cfs_add_epf_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct config_group * pci_ep_cfs_add_epf_group(const char * name)
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
