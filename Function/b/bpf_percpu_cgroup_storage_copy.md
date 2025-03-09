# Function: <code>bpf_percpu_cgroup_storage_copy</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779328,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:157",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779328,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580863968,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863968,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914992,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914992,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062080,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062080,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074112,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:183",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074112,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089104,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:184",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089104,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318112,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:182",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318112,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581619872,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:182",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581619872,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004720,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:182",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004720,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582195744,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:182",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582195744,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344656,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:182",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344656,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492248392,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492248392,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226141384,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226141384,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285476848,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285476848,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272391136,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272391136,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883792,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883792,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580829856,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580829856,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875040,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875040,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933632,
      "name": "bpf_percpu_cgroup_storage_copy",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:170",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933632,
      "name": "bpf_percpu_cgroup_storage_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map * _map, void * _key, void * value)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * key</code>
</li>
<li>
<b>Param removed. </b>
<code>void * _key</code>
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
