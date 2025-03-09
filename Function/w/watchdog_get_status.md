# Function: <code>watchdog_get_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585707010,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:165",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586102464,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:294",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586102464,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586302944,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:295",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586302944,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586401872,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:303",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401872,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586867904,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:304",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586867904,
      "name": "watchdog_get_status",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587161408,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:324",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587161408,
      "name": "watchdog_get_status",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587341328,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:324",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587341328,
      "name": "watchdog_get_status",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587612144,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:341",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587612144,
      "name": "watchdog_get_status",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587815920,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:340",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587815920,
      "name": "watchdog_get_status",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588662768,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:341",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588662768,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588689824,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:342",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588689824,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588576192,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:342",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588576192,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589251872,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:326",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589251872,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590720144,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:322",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590720144,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592394672,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:329",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592394672,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592823856,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:331",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592823856,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593573120,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:331",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593573120,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501031840,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:340",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501031840,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233549052,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:340",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233549052,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294511472,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:340",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294511472,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277769596,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:340",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277769596,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587446896,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:340",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446896,
      "name": "watchdog_get_status",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215104,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:340",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215104,
      "name": "watchdog_get_status",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587772064,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:340",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772064,
      "name": "watchdog_get_status",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device * wdd)
```

```json
{
  "name": "watchdog_get_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587885408,
      "name": "watchdog_get_status",
      "external": false,
      "loc": "drivers/watchdog/watchdog_dev.c:340",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:status_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885408,
      "name": "watchdog_get_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
unsigned int watchdog_get_status(struct watchdog_device * wdd)
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
