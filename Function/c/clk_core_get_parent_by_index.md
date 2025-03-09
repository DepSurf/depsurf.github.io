# Function: <code>clk_core_get_parent_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586078480,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:348",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_hw_get_parent_by_index",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078480,
      "name": "clk_core_get_parent_by_index",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586487072,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:250",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_fetch_parent_index",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586487072,
      "name": "clk_core_get_parent_by_index",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293792,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:250",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_fetch_parent_index",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293792,
      "name": "clk_core_get_parent_by_index",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372880,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:250",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372880,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584779792,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:304",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779792,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585007552,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:319",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585007552,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585114112,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:317",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585114112,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585319504,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:435",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319504,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585455904,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:441",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585455904,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586174752,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:445",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_core_reparent_orphans_nolock",
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174752,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293824,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:445",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_core_reparent_orphans_nolock",
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293824,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586167264,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:445",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167264,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586668960,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:445",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586668960,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587940880,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:439",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587940880,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589298256,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:439",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_core_forward_rate_req",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589298256,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589595392,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:450",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_core_forward_rate_req",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589595392,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589905184,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:450",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_core_forward_rate_req",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589905184,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497746256,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:441",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497746256,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230568988,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:441",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230568988,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275891568,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:441",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275891568,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218432,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:441",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218432,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585170608,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:441",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585170608,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585406304,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:441",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406304,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
```

```json
{
  "name": "clk_core_get_parent_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585513792,
      "name": "clk_core_get_parent_by_index",
      "external": false,
      "loc": "drivers/clk/clk.c:441",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:possible_parent_show",
        "drivers/clk/clk.c:__clk_init_parent",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_hw_get_parent_by_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513792,
      "name": "clk_core_get_parent_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct clk_core * clk_core_get_parent_by_index(struct clk_core * core, u8 index)
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
