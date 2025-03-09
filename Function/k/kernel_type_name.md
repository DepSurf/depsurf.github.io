# Function: <code>kernel_type_name</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * kernel_type_name(u32 id)
```

```json
{
  "name": "kernel_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580991436,
      "name": "kernel_type_name",
      "external": true,
      "loc": "kernel/bpf/verifier.c:536",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:print_verifier_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008272,
      "name": "kernel_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
const char * kernel_type_name(const struct btf * btf, u32 id)
```

```json
{
  "name": "kernel_type_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580972361,
      "name": "kernel_type_name",
      "external": false,
      "loc": "kernel/bpf/verifier.c:561",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:print_verifier_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950288,
      "name": "kernel_type_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
const char * kernel_type_name(const struct btf * btf, u32 id)
```

```json
{
  "name": "kernel_type_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580968307,
      "name": "kernel_type_name",
      "external": false,
      "loc": "kernel/bpf/verifier.c:609",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:print_verifier_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954592,
      "name": "kernel_type_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
const char * kernel_type_name(const struct btf * btf, u32 id)
```

```json
{
  "name": "kernel_type_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581177113,
      "name": "kernel_type_name",
      "external": false,
      "loc": "kernel/bpf/verifier.c:610",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:print_verifier_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159488,
      "name": "kernel_type_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
const char * kernel_type_name(const struct btf * btf, u32 id)
```

```json
{
  "name": "kernel_type_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581487195,
      "name": "kernel_type_name",
      "external": false,
      "loc": "kernel/bpf/verifier.c:631",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:print_verifier_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437008,
      "name": "kernel_type_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
const char * kernel_type_name(const struct btf * btf, u32 id)
```

```json
{
  "name": "kernel_type_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581823699,
      "name": "kernel_type_name",
      "external": false,
      "loc": "kernel/bpf/verifier.c:691",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:print_verifier_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790192,
      "name": "kernel_type_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
const char * kernel_type_name(u32 id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf * btf</code>
</li>
<li>
<b>Param reordered. </b>
<code>id</code> ➡️ <code>btf, id</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
const char * kernel_type_name(const struct btf * btf, u32 id)
```
</details>
</li>
</ul>
