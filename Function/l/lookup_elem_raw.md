# Function: <code>lookup_elem_raw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580382400,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:128",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382400,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442384,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:282",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442384,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580496784,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:374",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496784,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525696,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:400",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525696,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589200,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:409",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589200,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684608,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:419",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    },
    {
      "addr": 18446744071580730592,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/sockmap.c:264",
      "file": "kernel/bpf/sockmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:__sock_hash_lookup_elem",
        "kernel/bpf/sockmap.c:sock_hash_delete_elem",
        "kernel/bpf/sockmap.c:sock_hash_get_next_key",
        "kernel/bpf/sockmap.c:bpf_tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684608,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071580730592,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755392,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755392,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839200,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839200,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890240,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890240,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035696,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:533",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035696,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044848,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:552",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044848,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059696,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:552",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059696,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284720,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:582",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284720,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580656,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:598",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580656,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958752,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:613",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958752,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147248,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:620",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147248,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296304,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:631",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296304,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492216976,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492216976,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226115048,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226115048,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285438320,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285438320,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272365154,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272365154,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580859040,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580859040,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580805168,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805168,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850288,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850288,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct htab_elem * lookup_elem_raw(struct hlist_nulls_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908608,
      "name": "lookup_elem_raw",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:421",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908608,
      "name": "lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct hlist_head * head</code> ➡️ <code>struct hlist_nulls_head * head</code>
</li>
</ul>
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
