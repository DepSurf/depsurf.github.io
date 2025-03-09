# Function: <code>hwspin_lock_free</code>

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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587305040,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:638",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305040,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:665",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587609673,
      "name": "hwspin_lock_free.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587608304,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:776",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738473,
      "name": "hwspin_lock_free.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587736816,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022693,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071588020608,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230227,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588228256,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:800",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105240,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071589103792,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:800",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615564,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071589103104,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:800",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591558651,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588992336,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:800",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592679261,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071589706416,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:800",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594564636,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071591214256,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592957664,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:800",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592957664,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593408032,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:800",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593408032,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594153744,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:805",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594153744,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501683800,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501683800,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234210604,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234210604,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295117680,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295117680,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278121726,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278121726,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587841923,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071587839952,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548253,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071587546864,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184707,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588182736,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hwspin_lock_free(struct hwspinlock * hwlock)
```

```json
{
  "name": "hwspin_lock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_free",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:798",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588302571,
      "name": "hwspin_lock_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588300784,
      "name": "hwspin_lock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hwspin_lock_free(struct hwspinlock * hwlock)
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
