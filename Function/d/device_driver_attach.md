# Function: <code>device_driver_attach</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586037376,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037376,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586184880,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:987",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184880,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586946592,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:961",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586946592,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587032176,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:1007",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032176,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586915984,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:1028",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586915984,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:1062",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592488869,
      "name": "device_driver_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587476688,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:1081",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594358431,
      "name": "device_driver_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071588797072,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:1100",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596246381,
      "name": "device_driver_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071590294272,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:1122",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596774815,
      "name": "device_driver_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071590614528,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:1122",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597684066,
      "name": "device_driver_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071590973632,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498983320,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:987",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498983320,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231552180,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:987",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231552180,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292135104,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:987",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292135104,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276360784,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:987",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276360784,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585945248,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:987",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945248,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794336,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:987",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794336,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586134896,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:987",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134896,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int device_driver_attach(struct device_driver * drv, struct device * dev)
```

```json
{
  "name": "device_driver_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586243488,
      "name": "device_driver_attach",
      "external": true,
      "loc": "drivers/base/dd.c:987",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bind_store",
        "drivers/base/dd.c:__driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586243488,
      "name": "device_driver_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int device_driver_attach(struct device_driver * drv, struct device * dev)
```
</details>
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
