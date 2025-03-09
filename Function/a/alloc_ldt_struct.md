# Function: <code>alloc_ldt_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ldt_struct * alloc_ldt_struct(int size)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052816,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:37",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:init_new_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052816,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
struct ldt_struct * alloc_ldt_struct(int size)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049120,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:37",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:init_new_context_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049120,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct ldt_struct * alloc_ldt_struct(unsigned int size)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048240,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:37",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:init_new_context_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048240,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579040576,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:38",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:init_new_context_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040576,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048784,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:65",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048784,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053584,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:65",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053584,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579058384,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:65",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058384,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066208,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:65",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066208,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068288,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:65",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068288,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076000,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:149",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076000,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078480,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:149",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078480,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085376,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:149",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085376,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108416,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:149",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108416,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139456,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:149",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139456,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183696,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:149",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183696,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579187776,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:149",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187776,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216992,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:149",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216992,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068640,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:65",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068640,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579001376,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:65",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001376,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068224,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:65",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068224,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```

```json
{
  "name": "alloc_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579072320,
      "name": "alloc_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:65",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072320,
      "name": "alloc_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int num_entries</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int size</code>
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
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct ldt_struct * alloc_ldt_struct(unsigned int num_entries)
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
