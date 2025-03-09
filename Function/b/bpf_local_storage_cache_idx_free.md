# Function: <code>bpf_local_storage_cache_idx_free</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache * cache, u16 idx)
```

```json
{
  "name": "bpf_local_storage_cache_idx_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139504,
      "name": "bpf_local_storage_cache_idx_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:463",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139504,
      "name": "bpf_local_storage_cache_idx_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache * cache, u16 idx)
```

```json
{
  "name": "bpf_local_storage_cache_idx_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095920,
      "name": "bpf_local_storage_cache_idx_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:469",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095920,
      "name": "bpf_local_storage_cache_idx_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache * cache, u16 idx)
```

```json
{
  "name": "bpf_local_storage_cache_idx_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581325280,
      "name": "bpf_local_storage_cache_idx_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:469",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581325280,
      "name": "bpf_local_storage_cache_idx_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache * cache, u16 idx)
```

```json
{
  "name": "bpf_local_storage_cache_idx_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581629168,
      "name": "bpf_local_storage_cache_idx_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:518",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629168,
      "name": "bpf_local_storage_cache_idx_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_local_storage_cache_idx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582016823,
      "name": "bpf_local_storage_cache_idx_free",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:528",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_local_storage_cache_idx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582209104,
      "name": "bpf_local_storage_cache_idx_free",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:708",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_local_storage_cache_idx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582358192,
      "name": "bpf_local_storage_cache_idx_free",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:689",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache * cache, u16 idx)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache * cache, u16 idx)
```
</details>
</li>
</ul>
