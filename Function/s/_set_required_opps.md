# Function: <code>_set_required_opps</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587531248,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:629",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531248,
      "name": "_set_required_opps.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:697",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587804048,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071587812542,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:745",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588009072,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071588017950,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:785",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862736,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071588876702,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, bool up)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588878032,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:801",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878032,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, bool up)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588764832,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:885",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764832,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, bool up)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:885",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589456496,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071592653033,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, bool up)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:1030",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590933392,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071594537617,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, bool up)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:957",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592635392,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596312994,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593080673,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:1000",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593835200,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:1065",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593835200,
      "name": "_set_required_opps.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501264136,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:745",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501264136,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233755000,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:745",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233755000,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294785056,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:745",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294785056,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277941598,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:745",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277941598,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:745",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587634064,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071587642942,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:745",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407936,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071587416814,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:745",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965216,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071587974094,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
```

```json
{
  "name": "_set_required_opps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_required_opps",
      "external": false,
      "loc": "drivers/opp/core.c:745",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080592,
      "name": "_set_required_opps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071588089470,
      "name": "_set_required_opps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool up</code>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int _set_required_opps(struct device * dev, struct opp_table * opp_table, struct dev_pm_opp * opp, bool up)
```
</details>
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
