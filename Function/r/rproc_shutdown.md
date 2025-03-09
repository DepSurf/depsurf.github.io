# Function: <code>rproc_shutdown</code>

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
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1801",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240604,
      "name": "rproc_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588237104,
      "name": "rproc_shutdown",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1865",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589117268,
      "name": "rproc_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589109456,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1849",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591619538,
      "name": "rproc_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589111328,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2047",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591562812,
      "name": "rproc_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589000752,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2065",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592681892,
      "name": "rproc_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589714704,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2063",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594567336,
      "name": "rproc_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071591222352,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592967904,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1987",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592967904,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593418288,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1988",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593418288,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594164240,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1988",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594164240,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501694928,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1801",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501694928,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234219960,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1801",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234219960,
      "name": "rproc_shutdown",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295130848,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1801",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295130848,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1801",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587852300,
      "name": "rproc_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587848800,
      "name": "rproc_shutdown",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void rproc_shutdown(struct rproc * rproc)
```

```json
{
  "name": "rproc_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_shutdown",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1801",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_sysfs.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312940,
      "name": "rproc_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588309440,
      "name": "rproc_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void rproc_shutdown(struct rproc * rproc)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
void rproc_shutdown(struct rproc * rproc)
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
void rproc_shutdown(struct rproc * rproc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void rproc_shutdown(struct rproc * rproc)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
