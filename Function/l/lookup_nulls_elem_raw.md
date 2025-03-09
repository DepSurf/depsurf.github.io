# Function: <code>lookup_nulls_elem_raw</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525568,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:417",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525568,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589072,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:426",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589072,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684480,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:436",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684480,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755488,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:450",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755488,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839312,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839312,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890352,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890352,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035808,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:550",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035808,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044960,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:569",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044960,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059808,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:569",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059808,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284832,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:599",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284832,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580784,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:615",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580784,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958896,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:630",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958896,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147392,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:637",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147392,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296448,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:648",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296448,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492217112,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492217112,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226115164,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226115164,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285438512,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285438512,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272365012,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272365012,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580859152,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580859152,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580805280,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805280,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850400,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850400,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```

```json
{
  "name": "lookup_nulls_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908720,
      "name": "lookup_nulls_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:438",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908720,
      "name": "lookup_nulls_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct htab_elem * lookup_nulls_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size, u32 n_buckets)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
