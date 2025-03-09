# Function: <code>bpf_map_area_alloc</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * bpf_map_area_alloc(size_t size)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470656,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:55",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470656,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * bpf_map_area_alloc(size_t size)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580490992,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:67",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490992,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * bpf_map_area_alloc(size_t size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546000,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:113",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546000,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * bpf_map_area_alloc(size_t size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580634608,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:137",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634608,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void * bpf_map_area_alloc(size_t size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692848,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:137",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692848,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void * bpf_map_area_alloc(size_t size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761504,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761504,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811552,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811552,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935856,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:303",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935856,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932496,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:311",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932496,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935504,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:312",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935504,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139344,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:331",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139344,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412032,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:337",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412032,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764992,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:337",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/cpumap.c:cpu_map_alloc",
        "kernel/bpf/cpumap.c:cpu_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764992,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926256,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:310",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "net/xdp/xskmap.c:xsk_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926256,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052688,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:311",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "net/xdp/xskmap.c:xsk_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052688,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492131944,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492131944,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226030588,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226030588,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285338800,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285338800,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272298088,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272298088,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780352,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780352,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726528,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726528,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771600,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771600,
      "name": "bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * bpf_map_area_alloc(u64 size, int numa_node)
```

```json
{
  "name": "bpf_map_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580829824,
      "name": "bpf_map_area_alloc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580829824,
      "name": "bpf_map_area_alloc",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void * bpf_map_area_alloc(size_t size)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int numa_node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>size_t size</code> ➡️ <code>u64 size</code>
</li>
</ul>
</details>
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
