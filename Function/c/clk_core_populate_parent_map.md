# Function: <code>clk_core_populate_parent_map</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585325632,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3510",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325632,
      "name": "clk_core_populate_parent_map.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585472315,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3559",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int clk_core_populate_parent_map(struct clk_core * core, const struct clk_init_data * init)
```

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586173760,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3649",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586173760,
      "name": "clk_core_populate_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int clk_core_populate_parent_map(struct clk_core * core, const struct clk_init_data * init)
```

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586292464,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3718",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292464,
      "name": "clk_core_populate_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int clk_core_populate_parent_map(struct clk_core * core, const struct clk_init_data * init)
```

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166256,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3727",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166256,
      "name": "clk_core_populate_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586667648,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3755",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667648,
      "name": "clk_core_populate_parent_map.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587939408,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3828",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939408,
      "name": "clk_core_populate_parent_map.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589297104,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:4017",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589297104,
      "name": "clk_core_populate_parent_map.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589594256,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:4069",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589594256,
      "name": "clk_core_populate_parent_map.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589904048,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:4115",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904048,
      "name": "clk_core_populate_parent_map.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497769140,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3559",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230586660,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3559",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275907838,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3559",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585234843,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3559",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585187019,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3559",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585422715,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3559",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_populate_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585530635,
      "name": "clk_core_populate_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3559",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int clk_core_populate_parent_map(struct clk_core * core, const struct clk_init_data * init)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int clk_core_populate_parent_map(struct clk_core * core, const struct clk_init_data * init)
```
</details>
</li>
</ul>
