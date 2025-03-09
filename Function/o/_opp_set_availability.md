# Function: <code>_opp_set_availability</code>

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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587057072,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:1697",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057072,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587355488,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:1588",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587355488,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587534928,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:1882",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587534928,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:1999",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808864,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587813364,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2048",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588014032,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071588018678,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2162",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588868736,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071588877743,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2259",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588885120,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071591596947,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2633",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772704,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    },
    {
      "addr": 18446744071591539928,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2643",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589464672,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
    },
    {
      "addr": 18446744071592654391,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2783",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590942400,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
    },
    {
      "addr": 18446744071594539019,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2780",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592644384,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
    },
    {
      "addr": 18446744071596313341,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2794",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593074880,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
    },
    {
      "addr": 18446744071596842195,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2878",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593826800,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
    },
    {
      "addr": 18446744071597767196,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501270648,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2048",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501270648,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233760696,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2048",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233760696,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294792384,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2048",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294792384,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277946776,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2048",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277946776,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2048",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639024,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587643670,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2048",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587412896,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587417542,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2048",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970176,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587974822,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
```

```json
{
  "name": "_opp_set_availability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_set_availability",
      "external": false,
      "loc": "drivers/opp/core.c:2048",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_disable",
        "drivers/opp/core.c:dev_pm_opp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085552,
      "name": "_opp_set_availability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071588090198,
      "name": "_opp_set_availability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int _opp_set_availability(struct device * dev, long unsigned int freq, bool availability_req)
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
