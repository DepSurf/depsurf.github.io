# Function: <code>bpf_prog_kallsyms_find</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475088,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:414",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475088,
      "name": "bpf_prog_kallsyms_find",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580533120,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:423",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533120,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580619360,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:502",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580619360,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580678368,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:625",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678368,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580745376,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745376,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580795984,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795984,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492107000,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492107000,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226011016,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226011016,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285314832,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285314832,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272283122,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272283122,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580764784,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764784,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580710960,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710960,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580756032,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756032,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
```

```json
{
  "name": "bpf_prog_kallsyms_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580814128,
      "name": "bpf_prog_kallsyms_find",
      "external": false,
      "loc": "kernel/bpf/core.c:667",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:is_bpf_text_address",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814128,
      "name": "bpf_prog_kallsyms_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct bpf_prog * bpf_prog_kallsyms_find(long unsigned int addr)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
