# Function: <code>i2c_dw_set_sda_hold</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587238832,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:174",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587238832,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:174",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506869,
      "name": "i2c_dw_set_sda_hold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587505936,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:174",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587710005,
      "name": "i2c_dw_set_sda_hold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587709072,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:386",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580132,
      "name": "i2c_dw_set_sda_hold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071588578592,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:386",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591579463,
      "name": "i2c_dw_set_sda_hold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071588602656,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:389",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591522216,
      "name": "i2c_dw_set_sda_hold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071588486800,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:389",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592631458,
      "name": "i2c_dw_set_sda_hold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071589155248,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:389",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594514936,
      "name": "i2c_dw_set_sda_hold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071590607728,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592268032,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:392",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592268032,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592693344,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:392",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592693344,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593438992,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:392",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593438992,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500875072,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:174",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500875072,
      "name": "i2c_dw_set_sda_hold",
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233383720,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:174",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233383720,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294336816,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:174",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294336816,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277667278,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:174",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277667278,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:174",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587666149,
      "name": "i2c_dw_set_sda_hold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587665216,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_sda_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_sda_hold",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:174",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772533,
      "name": "i2c_dw_set_sda_hold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587771600,
      "name": "i2c_dw_set_sda_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_dw_set_sda_hold(struct dw_i2c_dev * dev)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
