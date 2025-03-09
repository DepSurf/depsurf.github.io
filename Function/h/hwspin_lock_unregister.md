# Function: <code>hwspin_lock_unregister</code>

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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587304928,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:456",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304928,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587607600,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:483",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587607600,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587735824,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:512",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735824,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022674,
      "name": "hwspin_lock_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588020304,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588227952,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227952,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589102768,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589102768,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589102080,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589102080,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588991312,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588991312,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589706736,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589705312,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591214576,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591212992,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592958144,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592956112,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593408510,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593406480,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594154222,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:538",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594152192,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501683392,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501683392,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234210256,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234210256,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295115856,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295115856,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278120648,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278120648,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587839648,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587839648,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587546560,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587546560,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588182432,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182432,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
```

```json
{
  "name": "hwspin_lock_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588300480,
      "name": "hwspin_lock_unregister",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:534",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588300480,
      "name": "hwspin_lock_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int hwspin_lock_unregister(struct hwspinlock_device * bank)
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
