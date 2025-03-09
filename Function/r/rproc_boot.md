# Function: <code>rproc_boot</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1729",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240410,
      "name": "rproc_boot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588236880,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1793",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589117074,
      "name": "rproc_boot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071589109232,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1771",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591619090,
      "name": "rproc_boot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071589110992,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1969",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591562377,
      "name": "rproc_boot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071589000416,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1987",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592683125,
      "name": "rproc_boot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071589715472,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1983",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594568543,
      "name": "rproc_boot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071591223264,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592969360,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1907",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592969360,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593419728,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1908",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593419728,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594165680,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1908",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594165680,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501694448,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1729",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501694448,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234219520,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1729",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234219520,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295130288,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1729",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295130288,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1729",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587852106,
      "name": "rproc_boot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587848576,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int rproc_boot(struct rproc * rproc)
```

```json
{
  "name": "rproc_boot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_boot",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1729",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312746,
      "name": "rproc_boot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588309216,
      "name": "rproc_boot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int rproc_boot(struct rproc * rproc)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rproc_boot(struct rproc * rproc)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int rproc_boot(struct rproc * rproc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int rproc_boot(struct rproc * rproc)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
