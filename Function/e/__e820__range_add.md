# Function: <code>__e820__range_add</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596323336,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:133",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323336,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602641325,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:153",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602641325,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602810799,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:153",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602810799,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604605846,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:152",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604605846,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604701406,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604701406,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604713794,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604713794,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609060478,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609060478,
      "name": "__e820__range_add",
      "section": ".init.text",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612123838,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612123838,
      "name": "__e820__range_add",
      "section": ".init.text",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614263764,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614263764,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615185100,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615185100,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616951512,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616951512,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 109
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
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627571843,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__append_e820_table"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619323719,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__append_e820_table"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621616839,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__append_e820_table"
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604640084,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604640084,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604608018,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604608018,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604717876,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604717876,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "__e820__range_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604717906,
      "name": "__e820__range_add",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:166",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:__e820__range_update",
        "arch/x86/kernel/e820.c:e820__range_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604717906,
      "name": "__e820__range_add",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __e820__range_add(struct e820_table * table, u64 start, u64 size, enum e820_type type)
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
