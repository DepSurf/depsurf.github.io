# Function: <code>btf_type_seq_show</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580714928,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:2229",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714928,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580796416,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:2881",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580796416,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884320,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3371",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884320,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935280,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3370",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935280,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581097312,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:4562",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097312,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124544,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:5518",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124544,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144448,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:5711",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144448,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581377808,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:5764",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377808,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692672,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:6497",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692672,
      "name": "btf_type_seq_show",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582091552,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:6988",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091552,
      "name": "btf_type_seq_show",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582287888,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:7090",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582287888,
      "name": "btf_type_seq_show",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582445376,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:7154",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445376,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492274808,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3370",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492274808,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226163836,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3370",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226163836,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285506544,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3370",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285506544,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272410776,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3370",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272410776,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904080,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3370",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904080,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850144,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3370",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850144,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895328,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3370",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895328,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```

```json
{
  "name": "btf_type_seq_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953968,
      "name": "btf_type_seq_show",
      "external": true,
      "loc": "kernel/bpf/btf.c:3370",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/arraymap.c:prog_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem",
        "kernel/bpf/arraymap.c:array_map_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953968,
      "name": "btf_type_seq_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void btf_type_seq_show(const struct btf * btf, u32 type_id, void * obj, struct seq_file * m)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
