# Function: <code>hwspin_lock_request_specific</code>

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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587306144,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:590",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587306144,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:617",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587609617,
      "name": "hwspin_lock_request_specific.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587608128,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:728",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738417,
      "name": "hwspin_lock_request_specific.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587736512,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023017,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071588021456,
      "name": "hwspin_lock_request_specific",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230456,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071588229072,
      "name": "hwspin_lock_request_specific",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:752",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105183,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589103504,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:752",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615507,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589102816,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:752",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591558594,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071588992048,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:752",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592679204,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589706112,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:752",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594564583,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591213936,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592957264,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:752",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592957264,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593407632,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:752",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593407632,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594153344,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:757",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594153344,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501685112,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501685112,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234211840,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234211840,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295117120,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295117120,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278121354,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278121354,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587842152,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587840768,
      "name": "hwspin_lock_request_specific",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548482,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587547680,
      "name": "hwspin_lock_request_specific",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184936,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071588183552,
      "name": "hwspin_lock_request_specific",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
```

```json
{
  "name": "hwspin_lock_request_specific",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_request_specific",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:750",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588302800,
      "name": "hwspin_lock_request_specific.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071588301600,
      "name": "hwspin_lock_request_specific",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct hwspinlock * hwspin_lock_request_specific(unsigned int id)
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
