# Function: <code>__clk_set_parent_after</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586081952,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1176",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_change_rate"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081952,
      "name": "__clk_set_parent_after.isra.19.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586492000,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1214",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586492000,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298720,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1214",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298720,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584374576,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1216",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584374576,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778896,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1293",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778896,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585013456,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1502",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585013456,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585120384,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1618",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585120384,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585328352,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1754",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328352,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585466384,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1762",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585466384,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586184224,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1783",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_reparent_orphans_nolock",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184224,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586303856,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1792",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_reparent_orphans_nolock",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303856,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586174400,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1813",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174400,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586679376,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1813",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586679376,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587950384,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1827",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587950384,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589309008,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:2007",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589309008,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589607808,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:2052",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589607808,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589917840,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:2052",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589917840,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497761040,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1762",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_reparent_orphans_nolock",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497761040,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230580996,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1762",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_reparent_orphans_nolock",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230580996,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275901540,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1762",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_reparent_orphans_nolock",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275901540,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585228912,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1762",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585228912,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585181088,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1762",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585181088,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416784,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1762",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416784,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```

```json
{
  "name": "__clk_set_parent_after",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585524480,
      "name": "__clk_set_parent_after",
      "external": false,
      "loc": "drivers/clk/clk.c:1762",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585524480,
      "name": "__clk_set_parent_after",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
```
</details>
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
void __clk_set_parent_after(struct clk_core * core, struct clk_core * parent, struct clk_core * old_parent)
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
