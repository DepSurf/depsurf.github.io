# Function: <code>bpf_sk_storage_map_seq_find_next</code>

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
struct bpf_local_storage_elem * bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info * info, struct bpf_local_storage_elem * prev_selem)
```

```json
{
  "name": "bpf_sk_storage_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589761760,
      "name": "bpf_sk_storage_map_seq_find_next",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:730",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589761760,
      "name": "bpf_sk_storage_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
struct bpf_local_storage_elem * bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info * info, struct bpf_local_storage_elem * prev_selem)
```

```json
{
  "name": "bpf_sk_storage_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589665376,
      "name": "bpf_sk_storage_map_seq_find_next",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:730",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589665376,
      "name": "bpf_sk_storage_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_local_storage_elem * bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info * info, struct bpf_local_storage_elem * prev_selem)
```

```json
{
  "name": "bpf_sk_storage_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_storage_map_seq_find_next",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:729",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590422208,
      "name": "bpf_sk_storage_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071592709041,
      "name": "bpf_sk_storage_map_seq_find_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_local_storage_elem * bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info * info, struct bpf_local_storage_elem * prev_selem)
```

```json
{
  "name": "bpf_sk_storage_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_storage_map_seq_find_next",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:740",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592020992,
      "name": "bpf_sk_storage_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071594595339,
      "name": "bpf_sk_storage_map_seq_find_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_local_storage_elem * bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info * info, struct bpf_local_storage_elem * prev_selem)
```

```json
{
  "name": "bpf_sk_storage_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_storage_map_seq_find_next",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:710",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593836480,
      "name": "bpf_sk_storage_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071596332056,
      "name": "bpf_sk_storage_map_seq_find_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
struct bpf_local_storage_elem * bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info * info, struct bpf_local_storage_elem * prev_selem)
```

```json
{
  "name": "bpf_sk_storage_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_storage_map_seq_find_next",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:708",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594211008,
      "name": "bpf_sk_storage_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071596860843,
      "name": "bpf_sk_storage_map_seq_find_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
struct bpf_local_storage_elem * bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info * info, struct bpf_local_storage_elem * prev_selem)
```

```json
{
  "name": "bpf_sk_storage_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_storage_map_seq_find_next",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:709",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595008368,
      "name": "bpf_sk_storage_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071597785950,
      "name": "bpf_sk_storage_map_seq_find_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
struct bpf_local_storage_elem * bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info * info, struct bpf_local_storage_elem * prev_selem)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
