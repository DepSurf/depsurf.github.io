# Function: <code>watchdog_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585705856,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:128",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585705856,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586104112,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:257",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586104112,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586304800,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:258",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304800,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586403568,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:266",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403568,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586869728,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:267",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586869728,
      "name": "watchdog_stop",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:287",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587163216,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587166178,
      "name": "watchdog_stop.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587343181,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:287",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587343136,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587346100,
      "name": "watchdog_stop.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587614417,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:304",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587614016,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587617091,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587818952,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587818320,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587820870,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588666072,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:304",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588665328,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071588667880,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588693208,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:305",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588692464,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071591583620,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588579576,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:305",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588578832,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071591526665,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589255416,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:288",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254672,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071592637701,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:284",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590723344,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071594521496,
      "name": "watchdog_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592396000,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:290",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396000,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592825344,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:292",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592825344,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593574608,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:292",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593574608,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501033312,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501033312,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233551168,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233551168,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294516128,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294515552,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277771652,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277771652,
      "name": "watchdog_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587449928,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449296,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587451846,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587218136,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587217504,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587220054,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587775096,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587774464,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587777014,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587888440,
      "name": "watchdog_stop",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887808,
      "name": "watchdog_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587890358,
      "name": "watchdog_stop.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int watchdog_stop(struct watchdog_device * wdd)
```
</details>
</li>
</ul>
