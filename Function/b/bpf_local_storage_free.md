# Function: <code>bpf_local_storage_free</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_local_storage_free(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool bpf_ma, bool reuse_now)
```

```json
{
  "name": "bpf_local_storage_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582203680,
      "name": "bpf_local_storage_free",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:156",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203680,
      "name": "bpf_local_storage_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_local_storage_free(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool bpf_ma, bool reuse_now)
```

```json
{
  "name": "bpf_local_storage_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582352912,
      "name": "bpf_local_storage_free",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:156",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352912,
      "name": "bpf_local_storage_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void bpf_local_storage_free(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool bpf_ma, bool reuse_now)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
