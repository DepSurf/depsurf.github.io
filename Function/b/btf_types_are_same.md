# Function: <code>btf_types_are_same</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_types_are_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581121529,
      "name": "btf_types_are_same",
      "external": false,
      "loc": "kernel/bpf/btf.c:5031",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match"
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
  "name": "btf_types_are_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581140473,
      "name": "btf_types_are_same",
      "external": false,
      "loc": "kernel/bpf/btf.c:5104",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_types_are_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581373305,
      "name": "btf_types_are_same",
      "external": false,
      "loc": "kernel/bpf/btf.c:5157",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_types_are_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581689959,
      "name": "btf_types_are_same",
      "external": false,
      "loc": "kernel/bpf/btf.c:5704",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool btf_types_are_same(const struct btf * btf1, u32 id1, const struct btf * btf2, u32 id2)
```

```json
{
  "name": "btf_types_are_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582087815,
      "name": "btf_types_are_same",
      "external": true,
      "loc": "kernel/bpf/btf.c:6373",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582087328,
      "name": "btf_types_are_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
bool btf_types_are_same(const struct btf * btf1, u32 id1, const struct btf * btf2, u32 id2)
```

```json
{
  "name": "btf_types_are_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582284170,
      "name": "btf_types_are_same",
      "external": true,
      "loc": "kernel/bpf/btf.c:6461",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283680,
      "name": "btf_types_are_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
bool btf_types_are_same(const struct btf * btf1, u32 id1, const struct btf * btf2, u32 id2)
```

```json
{
  "name": "btf_types_are_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440954,
      "name": "btf_types_are_same",
      "external": true,
      "loc": "kernel/bpf/btf.c:6633",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440464,
      "name": "btf_types_are_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool btf_types_are_same(const struct btf * btf1, u32 id1, const struct btf * btf2, u32 id2)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
