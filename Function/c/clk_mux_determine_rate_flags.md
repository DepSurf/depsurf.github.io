# Function: <code>clk_mux_determine_rate_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586078624,
      "name": "clk_mux_determine_rate_flags",
      "external": false,
      "loc": "drivers/clk/clk.c:454",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078624,
      "name": "clk_mux_determine_rate_flags.isra.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586488112,
      "name": "clk_mux_determine_rate_flags",
      "external": false,
      "loc": "drivers/clk/clk.c:355",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586488112,
      "name": "clk_mux_determine_rate_flags.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584294832,
      "name": "clk_mux_determine_rate_flags",
      "external": false,
      "loc": "drivers/clk/clk.c:355",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294832,
      "name": "clk_mux_determine_rate_flags.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584377904,
      "name": "clk_mux_determine_rate_flags",
      "external": false,
      "loc": "drivers/clk/clk.c:355",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377904,
      "name": "clk_mux_determine_rate_flags.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584785984,
      "name": "clk_mux_determine_rate_flags",
      "external": false,
      "loc": "drivers/clk/clk.c:409",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785984,
      "name": "clk_mux_determine_rate_flags.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585011952,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:428",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011952,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118816,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:426",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118816,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585324976,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:541",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324976,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585463488,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:547",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585463488,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586174960,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:551",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174960,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586294032,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:545",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586294032,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586167472,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:545",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167472,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586669168,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:545",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586669168,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587941152,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:539",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941152,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589309424,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:586",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589309424,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 939
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589605920,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:638",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589605920,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589915952,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:638",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589915952,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497754472,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:547",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate",
        "drivers/clk/meson/clk-regmap.c:clk_regmap_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497754472,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230579152,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:547",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate",
        "drivers/clk/meson/clk-regmap.c:clk_regmap_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230579152,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275899660,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:547",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275899660,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585226016,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:547",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585226016,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585178192,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:547",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585178192,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585413888,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:547",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413888,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```

```json
{
  "name": "clk_mux_determine_rate_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585521472,
      "name": "clk_mux_determine_rate_flags",
      "external": true,
      "loc": "drivers/clk/clk.c:547",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_mux_determine_rate_closest",
        "drivers/clk/clk.c:__clk_mux_determine_rate",
        "drivers/clk/clk-mux.c:clk_mux_determine_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521472,
      "name": "clk_mux_determine_rate_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw * hw, struct clk_rate_request * req, long unsigned int flags)
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
