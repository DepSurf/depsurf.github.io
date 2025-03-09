# Function: <code>__device_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584454080,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1345",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454080,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584790304,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1351",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584790304,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584982192,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1425",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982192,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066752,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1428",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066752,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585489584,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1519",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585489584,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1704",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585734256,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1141
    },
    {
      "addr": 18446744071585743986,
      "name": "__device_suspend.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1706",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585866960,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
    },
    {
      "addr": 18446744071585876722,
      "name": "__device_suspend.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1692",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586103968,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1233
    },
    {
      "addr": 18446744071586113940,
      "name": "__device_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1713",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251536,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1233
    },
    {
      "addr": 18446744071586261364,
      "name": "__device_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587019040,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1591",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587019040,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587103632,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1590",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587103632,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586991856,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1591",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586991856,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587558080,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1610",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587558080,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1035
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588889328,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1606",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588889328,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1042
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590399248,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1606",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590399248,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1042
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1606",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590716864,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
    },
    {
      "addr": 18446744071596775693,
      "name": "__device_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1605",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591079024,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
    },
    {
      "addr": 18446744071597684943,
      "name": "__device_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499071456,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1713",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499071456,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231624392,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1713",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231624392,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292248624,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1713",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292248624,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2124
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1713",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586014320,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1792
    },
    {
      "addr": 18446744071586024692,
      "name": "__device_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1713",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585860864,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1221
    },
    {
      "addr": 18446744071585870644,
      "name": "__device_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1713",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586201552,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1233
    },
    {
      "addr": 18446744071586211380,
      "name": "__device_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
```

```json
{
  "name": "__device_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_suspend",
      "external": false,
      "loc": "drivers/base/power/main.c:1713",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586308304,
      "name": "__device_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1265
    },
    {
      "addr": 18446744071586320452,
      "name": "__device_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
int __device_suspend(struct device * dev, pm_message_t state, bool async)
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
