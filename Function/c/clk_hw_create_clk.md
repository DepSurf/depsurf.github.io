# Function: <code>clk_hw_create_clk</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585336480,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3466",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336480,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585475168,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3515",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585475168,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586194784,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3605",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194784,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586295304,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3656",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:devm_clk_hw_get_clk"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:devm_clk_hw_get_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293008,
      "name": "clk_hw_create_clk.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071586314640,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586187696,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3665",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:devm_clk_hw_get_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187696,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586689472,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3693",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:devm_clk_hw_get_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586689472,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587961280,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3765",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:devm_clk_hw_get_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961280,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589322688,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3954",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:devm_clk_hw_get_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322688,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589620800,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:4006",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:devm_clk_hw_get_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589620800,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589930800,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:4052",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:devm_clk_hw_get_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589930800,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497771992,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3515",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__of_clk_get",
        "drivers/clk/clk.c:of_clk_get_from_provider"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:__of_clk_get",
        "drivers/clk/clk.c:of_clk_get_from_provider"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497753184,
      "name": "clk_hw_create_clk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446603336497771416,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230592972,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3515",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__of_clk_get",
        "drivers/clk/clk.c:of_clk_get_from_provider"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:__of_clk_get",
        "drivers/clk/clk.c:of_clk_get_from_provider"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230577428,
      "name": "clk_hw_create_clk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 3230592456,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275910490,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3515",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__of_clk_get",
        "drivers/clk/clk.c:of_clk_get_from_provider"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:__of_clk_get",
        "drivers/clk/clk.c:of_clk_get_from_provider"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275898354,
      "name": "clk_hw_create_clk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446743936275910040,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585237696,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3515",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585237696,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189872,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3515",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189872,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585425568,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3515",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585425568,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_hw_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533488,
      "name": "clk_hw_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3515",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533488,
      "name": "clk_hw_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct clk * clk_hw_create_clk(struct device * dev, struct clk_hw * hw, const char * dev_id, const char * con_id)
```
</details>
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
