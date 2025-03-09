# Function: <code>store_sampling_down_factor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874592,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:339",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor_gov_pol",
        "drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor_gov_sys"
      ]
    },
    {
      "addr": 18446744071585877465,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:162",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor_gov_pol",
        "drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor_gov_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874592,
      "name": "store_sampling_down_factor.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586274000,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:240",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586277008,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:120",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274000,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071586277008,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586478128,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:240",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586481200,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:148",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586478128,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071586481200,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602656,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:241",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586605792,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:148",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602656,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071586605792,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587085952,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:241",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587089024,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:148",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587085952,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587089024,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587384112,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:241",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587387120,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:148",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384112,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587387120,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587564224,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:241",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587567200,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:150",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587564224,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587567200,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587840000,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587842928,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587840000,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587842928,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044832,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588047760,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044832,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588047760,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588905120,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588908224,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588905120,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588908224,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588917696,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588920736,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917696,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588920736,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588806304,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588809312,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588806304,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588809312,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589498944,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589501952,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589498944,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071589501952,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501313600,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501317088,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501313600,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446603336501317088,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233800416,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233803616,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233800416,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 3233803616,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294847056,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294851488,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294847056,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 13835058055294851488,
      "name": "store_sampling_down_factor",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587669824,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587672752,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669824,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587672752,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587443696,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587446624,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587443696,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587446624,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000976,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588003904,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000976,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588003904,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_down_factor",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588116416,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588119344,
      "name": "store_sampling_down_factor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:147",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588116416,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588119344,
      "name": "store_sampling_down_factor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set * attr_set, const char * buf, size_t count)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
