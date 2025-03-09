# Function: <code>__clk_register</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3588",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585331840,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    },
    {
      "addr": 18446744071585337273,
      "name": "__clk_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585472096,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3637",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585472096,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586189120,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3727",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586189120,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586309216,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3796",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586309216,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586182320,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3805",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586182320,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586684064,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3833",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684064,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587954896,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3906",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587954896,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589315968,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:4095",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589315968,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589613552,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:4147",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589613552,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589923584,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:4193",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589923584,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497768952,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3637",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_hw_register",
        "drivers/clk/clk.c:clk_hw_register",
        "drivers/clk/clk.c:clk_hw_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497768952,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230586452,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3637",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_hw_register",
        "drivers/clk/clk.c:clk_hw_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230586452,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275907654,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3637",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_hw_register",
        "drivers/clk/clk.c:clk_hw_register",
        "drivers/clk/clk.c:clk_hw_register",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275907654,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 810
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585234624,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3637",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234624,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585186800,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3637",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186800,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585422496,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3637",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585422496,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
```

```json
{
  "name": "__clk_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585530416,
      "name": "__clk_register",
      "external": false,
      "loc": "drivers/clk/clk.c:3637",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk.c:of_clk_hw_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530416,
      "name": "__clk_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
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
struct clk * __clk_register(struct device * dev, struct device_node * np, struct clk_hw * hw)
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
