# Function: <code>copy_map_value_locked</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580837728,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837728,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888752,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888752,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027952,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:314",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027952,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035104,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:325",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035104,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046688,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:326",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046688,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271088,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:336",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271088,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581563552,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:350",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563552,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936656,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:367",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936656,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120272,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:368",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120272,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260800,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:374",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260800,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492214680,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492214680,
      "name": "copy_map_value_locked",
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226111828,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226111828,
      "name": "copy_map_value_locked",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285436160,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285436160,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272362772,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272362772,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857552,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857552,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803712,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803712,
      "name": "copy_map_value_locked",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848800,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848800,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```

```json
{
  "name": "copy_map_value_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907088,
      "name": "copy_map_value_locked",
      "external": true,
      "loc": "kernel/bpf/helpers.c:299",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907088,
      "name": "copy_map_value_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void copy_map_value_locked(struct bpf_map * map, void * dst, void * src, bool lock_src)
```
</details>
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
