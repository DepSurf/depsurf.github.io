# Function: <code>__nvm_find_target_type</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585636080,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:253",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585636080,
      "name": "__nvm_find_target_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585761984,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:253",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585761984,
      "name": "__nvm_find_target_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994224,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:241",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994224,
      "name": "__nvm_find_target_type",
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
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586141200,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:243",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141200,
      "name": "__nvm_find_target_type",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586899866,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:243",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586984730,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:239",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586866874,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:239",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498932352,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:243",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498932352,
      "name": "__nvm_find_target_type",
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
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231505168,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:243",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231505168,
      "name": "__nvm_find_target_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292068848,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:243",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292068848,
      "name": "__nvm_find_target_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276319454,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:243",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276319454,
      "name": "__nvm_find_target_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585901568,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:243",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585901568,
      "name": "__nvm_find_target_type",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586091216,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:243",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586091216,
      "name": "__nvm_find_target_type",
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
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```

```json
{
  "name": "__nvm_find_target_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586199824,
      "name": "__nvm_find_target_type",
      "external": false,
      "loc": "drivers/lightnvm/core.c:243",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register_tgt_type",
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586199824,
      "name": "__nvm_find_target_type",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct nvm_tgt_type * __nvm_find_target_type(const char * name)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
