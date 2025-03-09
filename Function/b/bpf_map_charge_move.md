# Function: <code>bpf_map_charge_move</code>

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
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761872,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:228",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761872,
      "name": "bpf_map_charge_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811936,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:231",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811936,
      "name": "bpf_map_charge_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580937934,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:385",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936256,
      "name": "bpf_map_charge_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492132512,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:231",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492132512,
      "name": "bpf_map_charge_move",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226031080,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:231",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226031080,
      "name": "bpf_map_charge_move",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285339504,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:231",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285339504,
      "name": "bpf_map_charge_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272300652,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:231",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272298540,
      "name": "bpf_map_charge_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780736,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:231",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780736,
      "name": "bpf_map_charge_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726912,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:231",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726912,
      "name": "bpf_map_charge_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771984,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:231",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771984,
      "name": "bpf_map_charge_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```

```json
{
  "name": "bpf_map_charge_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830208,
      "name": "bpf_map_charge_move",
      "external": true,
      "loc": "kernel/bpf/syscall.c:231",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830208,
      "name": "bpf_map_charge_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory * dst, struct bpf_map_memory * src)
```
</details>
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
