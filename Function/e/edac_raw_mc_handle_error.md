# Function: <code>edac_raw_mc_handle_error</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586562480,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1057",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562480,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1317
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587030000,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1062",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030000,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1335
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1064",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333398,
      "name": "edac_raw_mc_handle_error.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071587328288,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1057",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587511727,
      "name": "edac_raw_mc_handle_error.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071587506624,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1053",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785565,
      "name": "edac_raw_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071587780544,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1046",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587990301,
      "name": "edac_raw_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071587985248,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
void edac_raw_mc_handle_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588841248,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:986",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588841248,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void edac_raw_mc_handle_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588857088,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:990",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588857088,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void edac_raw_mc_handle_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:990",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591537145,
      "name": "edac_raw_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    },
    {
      "addr": 18446744071588743952,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
void edac_raw_mc_handle_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:993",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592650997,
      "name": "edac_raw_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    },
    {
      "addr": 18446744071589434416,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
void edac_raw_mc_handle_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:918",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594535496,
      "name": "edac_raw_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071590912464,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 914
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
void edac_raw_mc_handle_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592610368,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:917",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592610368,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1243
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
void edac_raw_mc_handle_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593040976,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:917",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593040976,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
void edac_raw_mc_handle_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593792416,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:918",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593792416,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501230560,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1046",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501230560,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1044
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233733556,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1046",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233733556,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1276
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294758832,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1046",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294758832,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1528
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277925110,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1046",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277925110,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1046",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587621277,
      "name": "edac_raw_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071587616224,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1046",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389293,
      "name": "edac_raw_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071587384240,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1046",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946445,
      "name": "edac_raw_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071587941392,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_raw_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_raw_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1046",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588061789,
      "name": "edac_raw_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071588056672,
      "name": "edac_raw_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1041
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void edac_raw_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, struct edac_raw_error_desc * e)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const enum hw_event_mc_err_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mem_ctl_info * mci</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, mci, e</code> ➡️ <code>e</code>
</li>
</ul>
</details>
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
