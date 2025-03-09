# Function: <code>sk_storage_update</code>

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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588622480,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:385",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622480,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588844768,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:387",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844768,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589730896,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:388",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589730896,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502418568,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:387",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502418568,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235153800,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:387",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235153800,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295970304,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:387",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295970304,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278623662,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:387",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278623662,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588451152,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:387",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588451152,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588163840,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:387",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588163840,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588783328,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:387",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588783328,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
```

```json
{
  "name": "sk_storage_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588923920,
      "name": "sk_storage_update",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:387",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588923920,
      "name": "sk_storage_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
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
struct bpf_sk_storage_data * sk_storage_update(struct sock * sk, struct bpf_map * map, void * value, u64 map_flags)
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
