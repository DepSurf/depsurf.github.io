# Function: <code>xen_manage_runstate_time</code>

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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859552,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859552,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585091210,
      "name": "xen_manage_runstate_time.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585090640,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201386,
      "name": "xen_manage_runstate_time.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585200816,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413914,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585413344,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554634,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585554064,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586273288,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586272656,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591448284,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586389856,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:85",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591390054,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586273840,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:85",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592433589,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071586786112,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:85",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594301649,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071588066352,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:85",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596230331,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589447456,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:85",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596758064,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589746912,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:85",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597666512,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590084928,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498215232,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498215232,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:86",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316346,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585315584,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505034,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585504464,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void xen_manage_runstate_time(int action)
```

```json
{
  "name": "xen_manage_runstate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_manage_runstate_time",
      "external": true,
      "loc": "drivers/xen/time.c:84",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585613018,
      "name": "xen_manage_runstate_time.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585612448,
      "name": "xen_manage_runstate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void xen_manage_runstate_time(int action)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_manage_runstate_time(int action)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_manage_runstate_time(int action)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_manage_runstate_time(int action)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xen_manage_runstate_time(int action)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
