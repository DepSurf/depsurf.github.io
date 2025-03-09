# Function: <code>clk_core_free_parent_map</code>

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
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585324400,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3572",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324400,
      "name": "clk_core_free_parent_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585462912,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3621",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462912,
      "name": "clk_core_free_parent_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void clk_core_free_parent_map(struct clk_core * core)
```

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586170896,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3711",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586170896,
      "name": "clk_core_free_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void clk_core_free_parent_map(struct clk_core * core)
```

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586289424,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3780",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586289424,
      "name": "clk_core_free_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void clk_core_free_parent_map(struct clk_core * core)
```

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586163232,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3789",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586163232,
      "name": "clk_core_free_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void clk_core_free_parent_map(struct clk_core * core)
```

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586664112,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3817",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664112,
      "name": "clk_core_free_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void clk_core_free_parent_map(struct clk_core * core)
```

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587936896,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3890",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587936896,
      "name": "clk_core_free_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void clk_core_free_parent_map(struct clk_core * core)
```

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589294480,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:4079",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589294480,
      "name": "clk_core_free_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void clk_core_free_parent_map(struct clk_core * core)
```

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589589904,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:4131",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589904,
      "name": "clk_core_free_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void clk_core_free_parent_map(struct clk_core * core)
```

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589899456,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:4177",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589899456,
      "name": "clk_core_free_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497752576,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3621",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497752576,
      "name": "clk_core_free_parent_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void clk_core_free_parent_map(struct clk_core * core)
```

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230567408,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3621",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230567408,
      "name": "clk_core_free_parent_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275897902,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3621",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275897902,
      "name": "clk_core_free_parent_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585225440,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3621",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585225440,
      "name": "clk_core_free_parent_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585177616,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3621",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585177616,
      "name": "clk_core_free_parent_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585413312,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3621",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413312,
      "name": "clk_core_free_parent_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_free_parent_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585520896,
      "name": "clk_core_free_parent_map",
      "external": false,
      "loc": "drivers/clk/clk.c:3621",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520896,
      "name": "clk_core_free_parent_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void clk_core_free_parent_map(struct clk_core * core)
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void clk_core_free_parent_map(struct clk_core * core)
```
</details>
</li>
</ul>
