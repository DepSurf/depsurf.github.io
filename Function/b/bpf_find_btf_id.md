# Function: <code>bpf_find_btf_id</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
s32 bpf_find_btf_id(const char * name, u32 kind, struct btf * * btf_p)
```

```json
{
  "name": "bpf_find_btf_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_find_btf_id",
      "external": false,
      "loc": "kernel/bpf/btf.c:537",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_kptrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676704,
      "name": "bpf_find_btf_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071593961357,
      "name": "bpf_find_btf_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
s32 bpf_find_btf_id(const char * name, u32 kind, struct btf * * btf_p)
```

```json
{
  "name": "bpf_find_btf_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_find_btf_id",
      "external": false,
      "loc": "kernel/bpf/btf.c:532",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582071104,
      "name": "bpf_find_btf_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071596021958,
      "name": "bpf_find_btf_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
s32 bpf_find_btf_id(const char * name, u32 kind, struct btf * * btf_p)
```

```json
{
  "name": "bpf_find_btf_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_find_btf_id",
      "external": false,
      "loc": "kernel/bpf/btf.c:555",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_kptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266864,
      "name": "bpf_find_btf_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071596543868,
      "name": "bpf_find_btf_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
s32 bpf_find_btf_id(const char * name, u32 kind, struct btf * * btf_p)
```

```json
{
  "name": "bpf_find_btf_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_find_btf_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:556",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_btf.c:btf_find_func_proto",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_kptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597447108,
      "name": "bpf_find_btf_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582421568,
      "name": "bpf_find_btf_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
s32 bpf_find_btf_id(const char * name, u32 kind, struct btf * * btf_p)
```
</details>
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
