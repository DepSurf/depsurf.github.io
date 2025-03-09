# Function: <code>bpf_selem_alloc</code>

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
struct bpf_local_storage_elem * bpf_selem_alloc(struct bpf_local_storage_map * smap, void * owner, void * value, bool charge_mem)
```

```json
{
  "name": "bpf_selem_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137072,
      "name": "bpf_selem_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:62",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137072,
      "name": "bpf_selem_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct bpf_local_storage_elem * bpf_selem_alloc(struct bpf_local_storage_map * smap, void * owner, void * value, bool charge_mem)
```

```json
{
  "name": "bpf_selem_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093456,
      "name": "bpf_selem_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:62",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093456,
      "name": "bpf_selem_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct bpf_local_storage_elem * bpf_selem_alloc(struct bpf_local_storage_map * smap, void * owner, void * value, bool charge_mem)
```

```json
{
  "name": "bpf_selem_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322640,
      "name": "bpf_selem_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:62",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322640,
      "name": "bpf_selem_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct bpf_local_storage_elem * bpf_selem_alloc(struct bpf_local_storage_map * smap, void * owner, void * value, bool charge_mem, gfp_t gfp_flags)
```

```json
{
  "name": "bpf_selem_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581625920,
      "name": "bpf_selem_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:65",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625920,
      "name": "bpf_selem_alloc",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_local_storage_elem * bpf_selem_alloc(struct bpf_local_storage_map * smap, void * owner, void * value, bool charge_mem, gfp_t gfp_flags)
```

```json
{
  "name": "bpf_selem_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582013328,
      "name": "bpf_selem_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:65",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013328,
      "name": "bpf_selem_alloc",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_local_storage_elem * bpf_selem_alloc(struct bpf_local_storage_map * smap, void * owner, void * value, bool charge_mem, gfp_t gfp_flags)
```

```json
{
  "name": "bpf_selem_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_selem_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:75",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596543194,
      "name": "bpf_selem_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582204192,
      "name": "bpf_selem_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_local_storage_elem * bpf_selem_alloc(struct bpf_local_storage_map * smap, void * owner, void * value, bool charge_mem, gfp_t gfp_flags)
```

```json
{
  "name": "bpf_selem_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_selem_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:75",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597446287,
      "name": "bpf_selem_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582353424,
      "name": "bpf_selem_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct bpf_local_storage_elem * bpf_selem_alloc(struct bpf_local_storage_map * smap, void * owner, void * value, bool charge_mem)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flags</code>
</li>
</ul>
</details>
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
