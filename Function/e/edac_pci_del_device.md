# Function: <code>edac_pci_del_device</code>

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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586576592,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576592,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043680,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043680,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587343293,
      "name": "edac_pci_del_device.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587342096,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587521453,
      "name": "edac_pci_del_device.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587520256,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587795291,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587794144,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000011,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587998864,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588854369,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588853984,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591594923,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588869328,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591538078,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588756192,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592651982,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071589447648,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:248",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594536562,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071590926528,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592626288,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:245",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592626288,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593056896,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:245",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593056896,
      "name": "edac_pci_del_device",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593808688,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:245",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593808688,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501244504,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501244504,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233747460,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233747460,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294778352,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294778352,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277937380,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277937380,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587630987,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587629840,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399003,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587397856,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956155,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587955008,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
```

```json
{
  "name": "edac_pci_del_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_pci_del_device",
      "external": true,
      "loc": "drivers/edac/edac_pci.c:249",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_release_generic_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588071499,
      "name": "edac_pci_del_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588070352,
      "name": "edac_pci_del_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct edac_pci_ctl_info * edac_pci_del_device(struct device * dev)
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
