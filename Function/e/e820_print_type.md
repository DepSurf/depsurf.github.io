# Function: <code>e820_print_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void e820_print_type(u32 type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594997506,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:134",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820_update_range",
        "arch/x86/kernel/e820.c:__e820_update_range",
        "arch/x86/kernel/e820.c:e820_print_map",
        "arch/x86/kernel/e820.c:e820_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594997506,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
void e820_print_type(u32 type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595160998,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:134",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_remove_range",
        "arch/x86/kernel/e820.c:__e820_update_range",
        "arch/x86/kernel/e820.c:__e820_update_range",
        "arch/x86/kernel/e820.c:e820_print_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595160998,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
void e820_print_type(u32 type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595403668,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:136",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_remove_range",
        "arch/x86/kernel/e820.c:__e820_update_range",
        "arch/x86/kernel/e820.c:__e820_update_range",
        "arch/x86/kernel/e820.c:e820_print_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595403668,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596323120,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:153",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323120,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 155
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602641109,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:173",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602641109,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 155
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602810867,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:174",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602810867,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 155
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604605914,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:173",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604605914,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 155
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604701474,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604701474,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 158
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604713862,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604713862,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 158
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609060545,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609060545,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612123905,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612123905,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614263832,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614263832,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615185168,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615185168,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616951621,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616951621,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 198
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627562208,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627562208,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 276
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619311552,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619311552,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 280
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621604672,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621604672,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 280
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604640152,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604640152,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 158
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604608086,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604608086,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 158
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604717944,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604717944,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 158
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
void e820_print_type(enum e820_type type)
```

```json
{
  "name": "e820_print_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604717974,
      "name": "e820_print_type",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:187",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__print_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604717974,
      "name": "e820_print_type",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 158
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 type</code> ➡️ <code>enum e820_type type</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void e820_print_type(enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void e820_print_type(enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void e820_print_type(enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void e820_print_type(enum e820_type type)
```
</details>
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
