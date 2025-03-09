# Function: <code>pci_reassign_bridge_resources</code>

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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057440,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2093",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057440,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256688,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2088",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256688,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584346448,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2090",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346448,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2059",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584542019,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071584539824,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2071",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584677211,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071584674960,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2123",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364071,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071585361632,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2124",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591398608,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071585513376,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2124",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591340840,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071585391936,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2124",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592368575,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071585853616,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2124",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594230923,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071587046736,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588228528,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2228",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588228528,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588504016,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2219",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588504016,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588802608,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2229",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588802608,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496925264,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2071",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496925264,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230201108,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2071",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230201108,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291024032,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2071",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291024032,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275610214,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2071",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275610214,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2071",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584627679,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071584625424,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2071",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557499,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071584555248,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2071",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584627371,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071584625120,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
```

```json
{
  "name": "pci_reassign_bridge_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_reassign_bridge_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:2071",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_resize_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735067,
      "name": "pci_reassign_bridge_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071584732816,
      "name": "pci_reassign_bridge_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int pci_reassign_bridge_resources(struct pci_dev * bridge, long unsigned int type)
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
