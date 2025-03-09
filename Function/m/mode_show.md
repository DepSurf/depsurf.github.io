# Function: <code>mode_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584751840,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:56",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585675440,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:613",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751840,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071585675440,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585077216,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1277",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585107088,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:57",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586074384,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:613",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077216,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071585107088,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586074384,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585263392,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1385",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585296144,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:57",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586285600,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:51",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263392,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071585296144,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586285600,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585346416,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1544",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585381312,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:57",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586384576,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:51",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346416,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071585381312,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586384576,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585774816,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1553",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585810400,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:57",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586847568,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:51",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585774816,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071585810400,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586847568,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586021648,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1551",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586058288,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:57",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587097408,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:60",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587139648,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586021648,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071586058288,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587097408,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587139648,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586160944,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1574",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586199168,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:57",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587274608,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:60",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587319536,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160944,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071586199168,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587274608,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587319536,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586397152,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1581",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586435392,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:49",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587544080,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587590400,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397152,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071586435392,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587544080,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587590400,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586543984,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1581",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586582384,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:49",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587746848,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587793840,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586543984,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071586582384,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587746848,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587793840,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587330352,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1561",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587367712,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:38",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588591600,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588640208,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330352,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071587367712,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071588591600,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588640208,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579709952,
      "name": "mode_show",
      "external": false,
      "loc": "kernel/reboot.c:618",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587392096,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1561",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587428880,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:38",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588614656,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588664144,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709952,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587392096,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071587428880,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071588614656,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588664144,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579717360,
      "name": "mode_show",
      "external": false,
      "loc": "kernel/reboot.c:618",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587273920,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1561",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587310752,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:38",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588499584,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588545072,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717360,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587273920,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071587310752,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071588499584,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588545072,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579795680,
      "name": "mode_show",
      "external": false,
      "loc": "kernel/reboot.c:697",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587841520,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1561",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587877648,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:38",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589168288,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589219152,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795680,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587841520,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071587877648,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071589168288,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589219152,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579903248,
      "name": "mode_show",
      "external": false,
      "loc": "kernel/reboot.c:1069",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589190864,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1318",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589227568,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:37",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590623360,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590681968,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903248,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071589190864,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071589227568,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071590623360,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071590681968,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580055616,
      "name": "mode_show",
      "external": false,
      "loc": "kernel/reboot.c:1086",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590745456,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1310",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590784400,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:39",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592285952,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592351008,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055616,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071590745456,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071590784400,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071592285952,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071592351008,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580110048,
      "name": "mode_show",
      "external": false,
      "loc": "kernel/reboot.c:1086",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591086800,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1310",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591125872,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:39",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592710464,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592777616,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110048,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071591086800,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071591125872,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071592710464,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071592777616,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580155088,
      "name": "mode_show",
      "external": false,
      "loc": "kernel/reboot.c:1109",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591431696,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1319",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591471456,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:39",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593456608,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593526688,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155088,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071591431696,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071591471456,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071593456608,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071593526688,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499432664,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1581",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500931576,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500994848,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499432664,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446603336500931576,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336500994848,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233173388,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/usb/musb/musb_core.c:1720",
      "file": "drivers/usb/musb/musb_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233441544,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233507844,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233173388,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 3233441544,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3233507844,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * page)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283385824,
      "name": "mode_show",
      "external": false,
      "loc": "arch/powerpc/perf/imc-pmu.c:55",
      "file": "arch/powerpc/perf/imc-pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292685456,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1581",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292737504,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:49",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294386832,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294469472,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283385824,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055292685456,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 13835058055292737504,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 13835058055294386832,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055294469472,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276658558,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1581",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277698270,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277746908,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276658558,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446743936277698270,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446743936277746908,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586234464,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1581",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586272864,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:49",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587387792,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587424816,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586234464,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071586272864,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587387792,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587424816,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586052832,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1581",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586091232,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:49",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587156000,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587193024,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586052832,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071586091232,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587156000,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587193024,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586491952,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1581",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586530352,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:49",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587702992,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587749984,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586491952,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071586530352,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587702992,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587749984,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t mode_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mode_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586603696,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1581",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586642080,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/nvdimm/pfn_devs.c:49",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587816064,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/pps/sysfs.c:46",
      "file": "drivers/pps/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587863184,
      "name": "mode_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:49",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603696,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071586642080,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587816064,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587863184,
      "name": "mode_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject * kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute * attr</code> ➡️ <code>struct kobj_attribute * attr</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * page</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buf</code>
</li>
</ul>
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
