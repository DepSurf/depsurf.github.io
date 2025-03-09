# Function: <code>bpf_map_init_from_attr</code>

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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580634704,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:161",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634704,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692944,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:161",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692944,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761600,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:173",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761600,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811664,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811664,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935936,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:330",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935936,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932576,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:338",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932576,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935584,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:339",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935584,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139424,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:358",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139424,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412128,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:364",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412128,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765136,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:364",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/cpumap.c:cpu_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765136,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926400,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:337",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "net/xdp/xskmap.c:xsk_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926400,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052832,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:338",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "net/xdp/xskmap.c:xsk_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052832,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492132128,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492132128,
      "name": "bpf_map_init_from_attr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226030736,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226030736,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285339072,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285339072,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272298244,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272298244,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780464,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780464,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726640,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726640,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771712,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771712,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
```

```json
{
  "name": "bpf_map_init_from_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580829936,
      "name": "bpf_map_init_from_attr",
      "external": true,
      "loc": "kernel/bpf/syscall.c:176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580829936,
      "name": "bpf_map_init_from_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_map_init_from_attr(struct bpf_map * map, union bpf_attr * attr)
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
