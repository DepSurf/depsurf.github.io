# Function: <code>__e820__mapped_all</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579057909,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:99",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type",
        "arch/x86/kernel/e820.c:e820__mapped_all"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579062821,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:99",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type",
        "arch/x86/kernel/e820.c:e820__mapped_all"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579067397,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:98",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type",
        "arch/x86/kernel/e820.c:e820__mapped_all"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579076085,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type",
        "arch/x86/kernel/e820.c:e820__mapped_all"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579078085,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type",
        "arch/x86/kernel/e820.c:e820__mapped_all"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct e820_entry * __e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579089093,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type"
      ],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__mapped_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088816,
      "name": "__e820__mapped_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
struct e820_entry * __e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579091045,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type"
      ],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__mapped_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090768,
      "name": "__e820__mapped_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
struct e820_entry * __e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579097589,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type"
      ],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__mapped_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097328,
      "name": "__e820__mapped_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
struct e820_entry * __e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579121253,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type"
      ],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__mapped_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120992,
      "name": "__e820__mapped_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
struct e820_entry * __e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579154005,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type"
      ],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__mapped_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153616,
      "name": "__e820__mapped_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct e820_entry * __e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579202501,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type"
      ],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__mapped_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202080,
      "name": "__e820__mapped_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct e820_entry * __e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579206965,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type"
      ],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__mapped_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206320,
      "name": "__e820__mapped_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
struct e820_entry * __e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579236309,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type"
      ],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__mapped_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235664,
      "name": "__e820__mapped_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579078437,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type",
        "arch/x86/kernel/e820.c:e820__mapped_all"
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
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579011125,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type",
        "arch/x86/kernel/e820.c:e820__mapped_all"
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
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579078021,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type",
        "arch/x86/kernel/e820.c:e820__mapped_all"
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
  "name": "__e820__mapped_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579082117,
      "name": "__e820__mapped_all",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:112",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__get_entry_type",
        "arch/x86/kernel/e820.c:e820__mapped_all"
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
struct e820_entry * __e820__mapped_all(u64 start, u64 end, enum e820_type type)
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
