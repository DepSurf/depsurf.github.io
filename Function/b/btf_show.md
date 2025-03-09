# Function: <code>btf_show</code>

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
void btf_show(struct btf_show * show, const char * fmt, void (anon))
```

```json
{
  "name": "btf_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086400,
      "name": "btf_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:997",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_df_show",
        "kernel/bpf/btf.c:btf_show_end_aggr_type",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086400,
      "name": "btf_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void btf_show(struct btf_show * show, const char * fmt, void (anon))
```

```json
{
  "name": "btf_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105520,
      "name": "btf_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:998",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_df_show",
        "kernel/bpf/btf.c:btf_show_end_aggr_type",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105520,
      "name": "btf_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void btf_show(struct btf_show * show, const char * fmt, void (anon))
```

```json
{
  "name": "btf_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335648,
      "name": "btf_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:998",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_df_show",
        "kernel/bpf/btf.c:btf_show_end_aggr_type",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335648,
      "name": "btf_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void btf_show(struct btf_show * show, const char * fmt, void (anon))
```

```json
{
  "name": "btf_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640928,
      "name": "btf_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:1093",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_df_show",
        "kernel/bpf/btf.c:btf_show_end_aggr_type",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640928,
      "name": "btf_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void btf_show(struct btf_show * show, const char * fmt, void (anon))
```

```json
{
  "name": "btf_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032144,
      "name": "btf_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:1096",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum64_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_df_show",
        "kernel/bpf/btf.c:btf_show_end_aggr_type",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032144,
      "name": "btf_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void btf_show(struct btf_show * show, const char * fmt, void (anon))
```

```json
{
  "name": "btf_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582225952,
      "name": "btf_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:1115",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum64_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_df_show",
        "kernel/bpf/btf.c:btf_show_end_aggr_type",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582225952,
      "name": "btf_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void btf_show(struct btf_show * show, const char * fmt, void (anon))
```

```json
{
  "name": "btf_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381904,
      "name": "btf_show",
      "external": false,
      "loc": "kernel/bpf/btf.c:1116",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum64_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_int128_print",
        "kernel/bpf/btf.c:btf_df_show",
        "kernel/bpf/btf.c:btf_show_end_aggr_type",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381904,
      "name": "btf_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void btf_show(struct btf_show * show, const char * fmt, void (anon))
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
