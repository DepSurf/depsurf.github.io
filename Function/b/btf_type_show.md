# Function: <code>btf_type_show</code>

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
void btf_type_show(const struct btf * btf, u32 type_id, void * obj, struct btf_show * show)
```

```json
{
  "name": "btf_type_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094048,
      "name": "btf_type_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:5486",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_type_snprintf_show",
        "kernel/bpf/btf.c:btf_type_seq_show_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094048,
      "name": "btf_type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void btf_type_show(const struct btf * btf, u32 type_id, void * obj, struct btf_show * show)
```

```json
{
  "name": "btf_type_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113120,
      "name": "btf_type_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:5679",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_type_snprintf_show",
        "kernel/bpf/btf.c:btf_type_seq_show_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113120,
      "name": "btf_type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void btf_type_show(const struct btf * btf, u32 type_id, void * obj, struct btf_show * show)
```

```json
{
  "name": "btf_type_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343520,
      "name": "btf_type_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:5732",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_type_snprintf_show",
        "kernel/bpf/btf.c:btf_type_seq_show_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343520,
      "name": "btf_type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void btf_type_show(const struct btf * btf, u32 type_id, void * obj, struct btf_show * show)
```

```json
{
  "name": "btf_type_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649040,
      "name": "btf_type_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:6465",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_type_snprintf_show",
        "kernel/bpf/btf.c:btf_type_seq_show_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649040,
      "name": "btf_type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
  "name": "btf_type_show",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582091725,
      "name": "btf_type_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:6956",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_snprintf_show",
        "kernel/bpf/btf.c:btf_type_seq_show_flags"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void btf_type_show(const struct btf * btf, u32 type_id, void * obj, struct btf_show * show)
```

```json
{
  "name": "btf_type_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234848,
      "name": "btf_type_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:7058",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_type_snprintf_show",
        "kernel/bpf/btf.c:btf_type_seq_show_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234848,
      "name": "btf_type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void btf_type_show(const struct btf * btf, u32 type_id, void * obj, struct btf_show * show)
```

```json
{
  "name": "btf_type_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582390944,
      "name": "btf_type_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:7122",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_type_snprintf_show",
        "kernel/bpf/btf.c:btf_type_seq_show_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390944,
      "name": "btf_type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void btf_type_show(const struct btf * btf, u32 type_id, void * obj, struct btf_show * show)
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void btf_type_show(const struct btf * btf, u32 type_id, void * obj, struct btf_show * show)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void btf_type_show(const struct btf * btf, u32 type_id, void * obj, struct btf_show * show)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
