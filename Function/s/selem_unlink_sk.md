# Function: <code>selem_unlink_sk</code>

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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588621472,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:193",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588621472,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588843504,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:196",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588843504,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589727376,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:197",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589727376,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502417104,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:196",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502417104,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235152104,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:196",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235152104,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295968016,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:196",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295968016,
      "name": "selem_unlink_sk",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278622412,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:196",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278622412,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588449888,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:196",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588449888,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588162576,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:196",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162576,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588782064,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:196",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588782064,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
```

```json
{
  "name": "selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588922656,
      "name": "selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:196",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:sk_storage_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922656,
      "name": "selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
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
void selem_unlink_sk(struct bpf_sk_storage_elem * selem)
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
