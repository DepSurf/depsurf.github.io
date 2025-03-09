# Function: <code>reset_control_acquire</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585525661,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:481",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527775,
      "name": "reset_control_acquire.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585525616,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585666640,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:480",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666640,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586391872,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:481",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391872,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586507008,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:555",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507008,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586391280,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:639",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391280,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586917853,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:639",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592445378,
      "name": "reset_control_acquire.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071586917792,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:640",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_acquire",
        "drivers/reset/core.c:reset_control_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594313407,
      "name": "reset_control_acquire.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071588210608,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:640",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_acquire",
        "drivers/reset/core.c:reset_control_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596232229,
      "name": "reset_control_acquire.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071589618672,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:640",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_acquire",
        "drivers/reset/core.c:reset_control_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596760138,
      "name": "reset_control_acquire.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071589922208,
      "name": "reset_control_acquire",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:640",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:reset_control_bulk_acquire",
        "drivers/reset/core.c:reset_control_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597668688,
      "name": "reset_control_acquire.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071590260704,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498334248,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:480",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498334248,
      "name": "reset_control_acquire",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231026808,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:480",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/tegra/pmc.c:tegra_powergate_init",
        "drivers/soc/tegra/pmc.c:tegra_genpd_power_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231026808,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291514816,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:480",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291514816,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276021814,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:480",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276021814,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585427664,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:480",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427664,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585297712,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:480",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297712,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585617040,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:480",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585617040,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585725168,
      "name": "reset_control_acquire",
      "external": true,
      "loc": "drivers/reset/core.c:480",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725168,
      "name": "reset_control_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int reset_control_acquire(struct reset_control * rstc)
```
</details>
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
