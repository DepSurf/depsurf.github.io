# Function: <code>btf_struct_walk</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int btf_struct_walk(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, u32 * next_btf_id)
```

```json
{
  "name": "btf_struct_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106608,
      "name": "btf_struct_walk",
      "external": false,
      "loc": "kernel/bpf/btf.c:4759",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106608,
      "name": "btf_struct_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
int btf_struct_walk(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, u32 * next_btf_id)
```

```json
{
  "name": "btf_struct_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125808,
      "name": "btf_struct_walk",
      "external": false,
      "loc": "kernel/bpf/btf.c:4832",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125808,
      "name": "btf_struct_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
int btf_struct_walk(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, u32 * next_btf_id)
```

```json
{
  "name": "btf_struct_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357632,
      "name": "btf_struct_walk",
      "external": false,
      "loc": "kernel/bpf/btf.c:4885",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357632,
      "name": "btf_struct_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
int btf_struct_walk(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, u32 * next_btf_id, enum bpf_type_flag * flag)
```

```json
{
  "name": "btf_struct_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669392,
      "name": "btf_struct_walk",
      "external": false,
      "loc": "kernel/bpf/btf.c:5415",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669392,
      "name": "btf_struct_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1530
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
int btf_struct_walk(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, u32 * next_btf_id, enum bpf_type_flag * flag)
```

```json
{
  "name": "btf_struct_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063488,
      "name": "btf_struct_walk",
      "external": false,
      "loc": "kernel/bpf/btf.c:6051",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063488,
      "name": "btf_struct_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1604
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
int btf_struct_walk(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, u32 * next_btf_id, enum bpf_type_flag * flag, const char * * field_name)
```

```json
{
  "name": "btf_struct_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258192,
      "name": "btf_struct_walk",
      "external": false,
      "loc": "kernel/bpf/btf.c:6125",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258192,
      "name": "btf_struct_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1761
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
int btf_struct_walk(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, u32 * next_btf_id, enum bpf_type_flag * flag, const char * * field_name)
```

```json
{
  "name": "btf_struct_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415152,
      "name": "btf_struct_walk",
      "external": false,
      "loc": "kernel/bpf/btf.c:6295",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415152,
      "name": "btf_struct_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1799
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int btf_struct_walk(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, u32 * next_btf_id)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_type_flag * flag</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * * field_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
