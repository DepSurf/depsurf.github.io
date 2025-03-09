# Function: <code>opp_debug_unregister</code>

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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587063152,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:222",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063152,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587361376,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:233",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361376,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587541248,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:233",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541248,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816083,
      "name": "opp_debug_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071587815872,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588021283,
      "name": "opp_debug_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071588021072,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588881216,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:224",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588881216,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588894160,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:224",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894160,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:224",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591541258,
      "name": "opp_debug_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588783056,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:224",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592656148,
      "name": "opp_debug_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589475296,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:236",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594540841,
      "name": "opp_debug_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071590954560,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592656880,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:255",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592656880,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593087616,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:254",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593087616,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593840016,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:254",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593840016,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501283976,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501283976,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233772528,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233772528,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294809680,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294809680,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277957598,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277957598,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646275,
      "name": "opp_debug_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071587646064,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420147,
      "name": "opp_debug_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071587419936,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977427,
      "name": "opp_debug_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071587977216,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_debug_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_debug_unregister",
      "external": true,
      "loc": "drivers/opp/debugfs.c:182",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092803,
      "name": "opp_debug_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071588092592,
      "name": "opp_debug_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void opp_debug_unregister(struct opp_device * opp_dev, struct opp_table * opp_table)
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
