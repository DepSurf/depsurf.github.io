# Function: <code>driver_deferred_probe_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584398488,
      "name": "driver_deferred_probe_add",
      "external": false,
      "loc": "drivers/base/dd.c:112",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584730512,
      "name": "driver_deferred_probe_add",
      "external": false,
      "loc": "drivers/base/dd.c:119",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730512,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584920304,
      "name": "driver_deferred_probe_add",
      "external": false,
      "loc": "drivers/base/dd.c:118",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920304,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585005248,
      "name": "driver_deferred_probe_add",
      "external": false,
      "loc": "drivers/base/dd.c:119",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585005248,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585427184,
      "name": "driver_deferred_probe_add",
      "external": false,
      "loc": "drivers/base/dd.c:144",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427184,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585670160,
      "name": "driver_deferred_probe_add",
      "external": false,
      "loc": "drivers/base/dd.c:141",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670160,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585799856,
      "name": "driver_deferred_probe_add",
      "external": false,
      "loc": "drivers/base/dd.c:119",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585799856,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586034384,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586034384,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586181792,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586181792,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586943232,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943232,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587028624,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:127",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028624,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586916256,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:131",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586911472,
      "name": "driver_deferred_probe_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071586912400,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587478306,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:131",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587473072,
      "name": "driver_deferred_probe_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071587474240,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588798887,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:132",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588794112,
      "name": "driver_deferred_probe_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071588794592,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590293503,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:132",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590289824,
      "name": "driver_deferred_probe_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071590290560,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590613759,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:132",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590610224,
      "name": "driver_deferred_probe_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071590610960,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590972863,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:132",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:driver_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590969296,
      "name": "driver_deferred_probe_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071590970064,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498979712,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498979712,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231548488,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231548488,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292130336,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292130336,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276357614,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276357614,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585942160,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942160,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585791248,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791248,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586131808,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131808,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```

```json
{
  "name": "driver_deferred_probe_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586240400,
      "name": "driver_deferred_probe_add",
      "external": true,
      "loc": "drivers/base/dd.c:123",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__device_attach_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586240400,
      "name": "driver_deferred_probe_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void driver_deferred_probe_add(struct device * dev)
```
</details>
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
