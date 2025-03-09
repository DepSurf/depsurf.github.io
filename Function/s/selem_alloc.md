# Function: <code>selem_alloc</code>

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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588622288,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:118",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622288,
      "name": "selem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588844576,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844576,
      "name": "selem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589730704,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589730704,
      "name": "selem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502418272,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502418272,
      "name": "selem_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235152944,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235152944,
      "name": "selem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295969280,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295969280,
      "name": "selem_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278623480,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278623480,
      "name": "selem_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588450960,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450960,
      "name": "selem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588163648,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588163648,
      "name": "selem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588783136,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588783136,
      "name": "selem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```

```json
{
  "name": "selem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588923728,
      "name": "selem_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588923728,
      "name": "selem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
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
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct bpf_sk_storage_elem * selem_alloc(struct bpf_sk_storage_map * smap, struct sock * sk, void * value, bool charge_omem)
```
</details>
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
