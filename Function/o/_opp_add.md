# Function: <code>_opp_add</code>

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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587059456,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1019",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587059456,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1063",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359173,
      "name": "_opp_add.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587357712,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1209",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587538976,
      "name": "_opp_add.cold.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071587537424,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1283",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587813652,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071587811456,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1332",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588018880,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071588016832,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1439",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878324,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588874944,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1523",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591597477,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588890720,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1695",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591540909,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071588779904,
      "name": "_opp_add",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1705",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592655690,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071589472144,
      "name": "_opp_add",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1849",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594540387,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071590950976,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1872",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596313601,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071592652464,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1880",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596842480,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071593083184,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1992",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597767559,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071593835600,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501274064,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1332",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501274064,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233763704,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1332",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233763704,
      "name": "_opp_add",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294796576,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1332",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294796576,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277949688,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1332",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277949688,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1332",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587643872,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071587641824,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1332",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417744,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071587415696,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1332",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975024,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071587972976,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table, bool rate_not_available)
```

```json
{
  "name": "_opp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_add",
      "external": true,
      "loc": "drivers/opp/core.c:1332",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_add_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090400,
      "name": "_opp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071588088352,
      "name": "_opp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int _opp_add(struct device * dev, struct dev_pm_opp * new_opp, struct opp_table * opp_table)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rate_not_available</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool rate_not_available</code>
</li>
</ul>
</details>
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
