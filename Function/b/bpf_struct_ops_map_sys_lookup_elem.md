# Function: <code>bpf_struct_ops_map_sys_lookup_elem</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_struct_ops_map_sys_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139024,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:241",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139024,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_struct_ops_map_sys_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172992,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:241",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172992,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_struct_ops_map_sys_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581191408,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:241",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191408,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_struct_ops_map_sys_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431664,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:242",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431664,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_struct_ops_map_sys_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758336,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:246",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758336,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_struct_ops_map_sys_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582174496,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:246",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174496,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_struct_ops_map_sys_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582372192,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:255",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582372192,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_struct_ops_map_sys_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582537840,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:255",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582537840,
      "name": "bpf_struct_ops_map_sys_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_struct_ops_map_sys_lookup_elem(struct bpf_map * map, void * key, void * value)
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
