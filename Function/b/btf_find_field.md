# Function: <code>btf_find_field</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int btf_find_field(const struct btf * btf, const struct btf_type * t, const char * name, int sz, int align)
```

```json
{
  "name": "btf_find_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343728,
      "name": "btf_find_field",
      "external": false,
      "loc": "kernel/bpf/btf.c:3106",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_find_timer",
        "kernel/bpf/btf.c:btf_find_spin_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343728,
      "name": "btf_find_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
int btf_find_field(const struct btf * btf, const struct btf_type * t, enum btf_field_type field_type, struct btf_field_info * info, int info_cnt)
```

```json
{
  "name": "btf_find_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581674256,
      "name": "btf_find_field",
      "external": false,
      "loc": "kernel/bpf/btf.c:3351",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_kptrs",
        "kernel/bpf/btf.c:btf_find_timer",
        "kernel/bpf/btf.c:btf_find_spin_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674256,
      "name": "btf_find_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
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
  "name": "btf_find_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582093507,
      "name": "btf_find_field",
      "external": false,
      "loc": "kernel/bpf/btf.c:3514",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse_fields"
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
  "name": "btf_find_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582290452,
      "name": "btf_find_field",
      "external": false,
      "loc": "kernel/bpf/btf.c:3552",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse_fields"
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
  "name": "btf_find_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582447940,
      "name": "btf_find_field",
      "external": false,
      "loc": "kernel/bpf/btf.c:3562",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse_fields"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int btf_find_field(const struct btf * btf, const struct btf_type * t, const char * name, int sz, int align)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum btf_field_type field_type</code>
</li>
<li>
<b>Param added. </b>
<code>struct btf_field_info * info</code>
</li>
<li>
<b>Param added. </b>
<code>int info_cnt</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * name</code>
</li>
<li>
<b>Param removed. </b>
<code>int sz</code>
</li>
<li>
<b>Param removed. </b>
<code>int align</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int btf_find_field(const struct btf * btf, const struct btf_type * t, enum btf_field_type field_type, struct btf_field_info * info, int info_cnt)
```
</details>
</li>
</ul>
