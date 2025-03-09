# Function: <code>bpf_map_area_free</code>

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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470736,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:74",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470736,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580491072,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:85",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491072,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546080,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:132",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/sockmap.c:sock_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546080,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580634688,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:156",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/sockmap.c:__bpf_htab_free",
        "kernel/bpf/sockmap.c:sock_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634688,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692928,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:156",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692928,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761584,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:156",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761584,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811648,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811648,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935920,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:313",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935920,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932560,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:321",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932560,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935568,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:322",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935568,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139408,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:341",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139408,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412096,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:347",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412096,
      "name": "bpf_map_area_free",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765088,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:347",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/bloom_filter.c:bloom_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_alloc",
        "kernel/bpf/offload.c:bpf_map_offload_map_free",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765088,
      "name": "bpf_map_area_free",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926352,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:320",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/bloom_filter.c:bloom_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_alloc",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/offload.c:bpf_map_offload_map_free",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_free",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_free",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926352,
      "name": "bpf_map_area_free",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052784,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:321",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/bloom_filter.c:bloom_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_alloc",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/offload.c:bpf_map_offload_map_free",
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/bpf/bpf_struct_ops.c:__bpf_struct_ops_map_free",
        "kernel/bpf/bpf_struct_ops.c:__bpf_struct_ops_map_free",
        "kernel/bpf/bpf_struct_ops.c:__bpf_struct_ops_map_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052784,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492132080,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492132080,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226030708,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226030708,
      "name": "bpf_map_area_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285339008,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:fd_array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285339008,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272298202,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272298202,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780448,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780448,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726624,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726624,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771696,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771696,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```

```json
{
  "name": "bpf_map_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580829920,
      "name": "bpf_map_area_free",
      "external": true,
      "loc": "kernel/bpf/syscall.c:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_free_elems",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580829920,
      "name": "bpf_map_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_area_free(void * area)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
