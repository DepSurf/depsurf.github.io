# Function: <code>bpf_map_charge_init</code>

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
int bpf_map_charge_init(struct bpf_map_memory * mem, size_t size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761664,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:200",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761664,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811728,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811728,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936000,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:357",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936000,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492132240,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492132240,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226030824,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226030824,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285339168,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285339168,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272298330,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272298330,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780528,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780528,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726704,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726704,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771776,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771776,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
```

```json
{
  "name": "bpf_map_charge_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830000,
      "name": "bpf_map_charge_init",
      "external": true,
      "loc": "kernel/bpf/syscall.c:203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830000,
      "name": "bpf_map_charge_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int bpf_map_charge_init(struct bpf_map_memory * mem, size_t size)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int bpf_map_charge_init(struct bpf_map_memory * mem, u64 size)
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
