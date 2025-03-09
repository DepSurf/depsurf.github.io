# Function: <code>shpchp_unconfigure_device</code>

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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584340720,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340720,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584435872,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435872,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632910,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071584632640,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770606,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071584770336,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:remove_board"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462076,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585461808,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:remove_board"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591415827,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585606544,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591358187,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585484944,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592386365,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585951664,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594250234,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071587155792,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596211145,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588364672,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596736293,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588640736,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597644877,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588941136,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497034448,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497034448,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275691484,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275691484,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719422,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071584719152,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584650190,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071584649920,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720766,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071584720496,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int shpchp_unconfigure_device(struct slot * p_slot)
```

```json
{
  "name": "shpchp_unconfigure_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_unconfigure_device",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_pci.c:64",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828350,
      "name": "shpchp_unconfigure_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071584828080,
      "name": "shpchp_unconfigure_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int shpchp_unconfigure_device(struct slot * p_slot)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
int shpchp_unconfigure_device(struct slot * p_slot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int shpchp_unconfigure_device(struct slot * p_slot)
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
