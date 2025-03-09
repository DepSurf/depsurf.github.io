# Function: <code>__sk_storage_lookup</code>

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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588620800,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:259",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588620800,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588842832,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:261",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588842832,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589726736,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:262",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589726736,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502416264,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:261",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502416264,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235151372,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:261",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235151372,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295967040,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:261",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295967040,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278621830,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:261",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278621830,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588449216,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:261",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588449216,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588161904,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:261",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588161904,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781392,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:261",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781392,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "__sk_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588921984,
      "name": "__sk_storage_lookup",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:261",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:sk_storage_delete",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588921984,
      "name": "__sk_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
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
struct bpf_sk_storage_data * __sk_storage_lookup(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_map * smap, bool cacheit_lockit)
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
