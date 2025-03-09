# Function: <code>rproc_trigger_recovery</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588240631,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1651",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240631,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1708",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589117995,
      "name": "rproc_trigger_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071589113552,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1686",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591619565,
      "name": "rproc_trigger_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071589111952,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1884",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591562951,
      "name": "rproc_trigger_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071589001760,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1902",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592683599,
      "name": "rproc_trigger_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071589716096,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1898",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594569010,
      "name": "rproc_trigger_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071591223952,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592972320,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1830",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592972320,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593422704,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1831",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593422704,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594168656,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1831",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store",
        "drivers/remoteproc/remoteproc_sysfs.c:recovery_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594168656,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501697656,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1651",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501697656,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234222456,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1651",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234222456,
      "name": "rproc_trigger_recovery",
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
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295134172,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1651",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295134172,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587852327,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1651",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587852327,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc * rproc)
```

```json
{
  "name": "rproc_trigger_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588312967,
      "name": "rproc_trigger_recovery",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1651",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312967,
      "name": "rproc_trigger_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int rproc_trigger_recovery(struct rproc * rproc)
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
int rproc_trigger_recovery(struct rproc * rproc)
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
int rproc_trigger_recovery(struct rproc * rproc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int rproc_trigger_recovery(struct rproc * rproc)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
