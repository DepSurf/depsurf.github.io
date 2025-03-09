# Function: <code>bpf_map_value_size</code>

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
u32 bpf_map_value_size(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_value_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927072,
      "name": "bpf_map_value_size",
      "external": false,
      "loc": "kernel/bpf/syscall.c:127",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_lookup_batch",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927072,
      "name": "bpf_map_value_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
u32 bpf_map_value_size(const struct bpf_map * map)
```

```json
{
  "name": "bpf_map_value_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924000,
      "name": "bpf_map_value_size",
      "external": false,
      "loc": "kernel/bpf/syscall.c:130",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_lookup_batch",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924000,
      "name": "bpf_map_value_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
u32 bpf_map_value_size(const struct bpf_map * map)
```

```json
{
  "name": "bpf_map_value_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580927360,
      "name": "bpf_map_value_size",
      "external": false,
      "loc": "kernel/bpf/syscall.c:131",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_lookup_batch",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927360,
      "name": "bpf_map_value_size",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 bpf_map_value_size(const struct bpf_map * map)
```

```json
{
  "name": "bpf_map_value_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581130416,
      "name": "bpf_map_value_size",
      "external": false,
      "loc": "kernel/bpf/syscall.c:150",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_lookup_batch",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130416,
      "name": "bpf_map_value_size",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 bpf_map_value_size(const struct bpf_map * map)
```

```json
{
  "name": "bpf_map_value_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581401024,
      "name": "bpf_map_value_size",
      "external": false,
      "loc": "kernel/bpf/syscall.c:154",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_lookup_batch",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401024,
      "name": "bpf_map_value_size",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 bpf_map_value_size(const struct bpf_map * map)
```

```json
{
  "name": "bpf_map_value_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581752384,
      "name": "bpf_map_value_size",
      "external": false,
      "loc": "kernel/bpf/syscall.c:154",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_lookup_batch",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752384,
      "name": "bpf_map_value_size",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 bpf_map_value_size(const struct bpf_map * map)
```

```json
{
  "name": "bpf_map_value_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581912368,
      "name": "bpf_map_value_size",
      "external": false,
      "loc": "kernel/bpf/syscall.c:127",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_lookup_batch",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912368,
      "name": "bpf_map_value_size",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 bpf_map_value_size(const struct bpf_map * map)
```

```json
{
  "name": "bpf_map_value_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582037216,
      "name": "bpf_map_value_size",
      "external": false,
      "loc": "kernel/bpf/syscall.c:130",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_lookup_batch",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037216,
      "name": "bpf_map_value_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
u32 bpf_map_value_size(struct bpf_map * map)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_map * map</code> ➡️ <code>const struct bpf_map * map</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
