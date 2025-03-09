# Function: <code>hwspin_lock_request</code>

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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587305968,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:547",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305968,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:574",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587609585,
      "name": "hwspin_lock_request.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587607984,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:685",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738385,
      "name": "hwspin_lock_request.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587736240,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022966,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071588021184,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230424,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588228800,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:709",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105151,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589103232,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:709",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615475,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589102544,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:709",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591558562,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588991776,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:709",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592679172,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589705840,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:709",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594564553,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071591213632,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592956912,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:709",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592956912,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593407280,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:709",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593407280,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594152992,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:714",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594152992,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501684776,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501684776,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234211496,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234211496,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295116672,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295116672,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278121072,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278121072,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587842120,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587840496,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548450,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587547408,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184904,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588183280,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
```

```json
{
  "name": "hwspin_lock_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:707",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588302768,
      "name": "hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588301328,
      "name": "hwspin_lock_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct hwspinlock * hwspin_lock_request()
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
