# Function: <code>watchdog_cdev_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586106070,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:809",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586306934,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:899",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586405798,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:907",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586872102,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:910",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587165584,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:930",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587345494,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:930",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587616416,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:956",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:960",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816976,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071587820703,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:981",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663824,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071588667713,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:982",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588690880,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
    },
    {
      "addr": 18446744071591583453,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:982",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588577248,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
    },
    {
      "addr": 18446744071591526498,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:988",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252992,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071592637493,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:993",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590721648,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
    },
    {
      "addr": 18446744071594521285,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1001",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396576,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 831
    },
    {
      "addr": 18446744071596309854,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1022",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592825920,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 831
    },
    {
      "addr": 18446744071596839228,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:1022",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593575184,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
    },
    {
      "addr": 18446744071597763365,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501037660,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:960",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233549496,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:960",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233549496,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294513296,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:960",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294513296,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277773696,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:960",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:960",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447952,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071587451679,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:960",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587216160,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071587219887,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:960",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587773120,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071587776847,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int watchdog_cdev_register(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_cdev_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_cdev_register",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:960",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587886464,
      "name": "watchdog_cdev_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071587890191,
      "name": "watchdog_cdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int watchdog_cdev_register(struct watchdog_device * wdd)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int watchdog_cdev_register(struct watchdog_device * wdd)
```
</details>
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
int watchdog_cdev_register(struct watchdog_device * wdd)
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
