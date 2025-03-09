# Function: <code>__clk_create_clk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct clk * __clk_create_clk(struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586087744,
      "name": "__clk_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:2479",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586087744,
      "name": "__clk_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct clk * __clk_create_clk(struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586499357,
      "name": "__clk_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:2487",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494832,
      "name": "__clk_create_clk.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071586498816,
      "name": "__clk_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct clk * __clk_create_clk(struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584306045,
      "name": "__clk_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:2490",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301536,
      "name": "__clk_create_clk.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071584305504,
      "name": "__clk_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct clk * __clk_create_clk(struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584384916,
      "name": "__clk_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:2523",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377680,
      "name": "__clk_create_clk.part.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071584384352,
      "name": "__clk_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct clk * __clk_create_clk(struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584791606,
      "name": "__clk_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:2654",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785760,
      "name": "__clk_create_clk.part.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071584791008,
      "name": "__clk_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct clk * __clk_create_clk(struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585020970,
      "name": "__clk_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:2911",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011728,
      "name": "__clk_create_clk.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071585020352,
      "name": "__clk_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct clk * __clk_create_clk(struct clk_hw * hw, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_create_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585128458,
      "name": "__clk_create_clk",
      "external": true,
      "loc": "drivers/clk/clk.c:3212",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
      ],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118592,
      "name": "__clk_create_clk.part.57",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071585127840,
      "name": "__clk_create_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct clk * __clk_create_clk(struct clk_hw * hw, const char * dev_id, const char * con_id)
```
</details>
</li>
</ul>
