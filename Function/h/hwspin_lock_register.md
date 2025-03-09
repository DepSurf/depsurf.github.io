# Function: <code>hwspin_lock_register</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587305392,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:408",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305392,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:435",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587609732,
      "name": "hwspin_lock_register.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587608608,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587737248,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:464",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738532,
      "name": "hwspin_lock_register.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587737152,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022599,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071588020064,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230171,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071588227712,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589104995,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071589102528,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615319,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071589101840,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591558406,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071588991072,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592679016,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071589705072,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594564397,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071591212736,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592955792,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592955792,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593406160,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593406160,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594151872,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:490",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594151872,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501683024,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501683024,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234209920,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234209920,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295118944,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295118944,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278122140,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278122140,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587841867,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587839408,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548197,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071587546320,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184651,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071588182192,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
```

```json
{
  "name": "hwspin_lock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_register",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588302515,
      "name": "hwspin_lock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071588300240,
      "name": "hwspin_lock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int hwspin_lock_register(struct hwspinlock_device * bank, struct device * dev, const struct hwspinlock_ops * ops, int base_id, int num_locks)
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
