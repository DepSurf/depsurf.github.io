# Function: <code>bpf_percpu_cgroup_storage_update</code>

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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779520,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:187",
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
      "addr": 18446744071580779520,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864160,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864160,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915184,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915184,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062272,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062272,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074320,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:212",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074320,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089312,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:213",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089312,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318368,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:211",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318368,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620176,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:211",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620176,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005056,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:211",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005056,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196080,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:211",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196080,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344992,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:211",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344992,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492248680,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492248680,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226141592,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226141592,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285477216,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285477216,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272391384,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272391384,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883984,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883984,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830048,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830048,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875232,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875232,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_percpu_cgroup_storage_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933856,
      "name": "bpf_percpu_cgroup_storage_update",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:200",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933856,
      "name": "bpf_percpu_cgroup_storage_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int bpf_percpu_cgroup_storage_update(struct bpf_map * _map, void * _key, void * value, u64 map_flags)
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
