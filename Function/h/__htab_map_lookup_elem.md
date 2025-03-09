# Function: <code>__htab_map_lookup_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580445552,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:295",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445552,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580499056,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:387",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580499056,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527968,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:440",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527968,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580591504,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:449",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591504,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580687312,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:459",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687312,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758256,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:473",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758256,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843472,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843472,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894512,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894512,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581044965,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:573",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035936,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581055488,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:592",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045088,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581070464,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:592",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059936,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581294000,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:622",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284960,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581592432,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:638",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580928,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581971680,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:653",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959056,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582162480,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:660",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147552,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582305488,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:671",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296608,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492222032,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492222032,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226119480,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226119480,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285445216,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285445216,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272369556,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272369556,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580863312,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863312,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580809440,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809440,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854560,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854560,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580912896,
      "name": "__htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
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
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912896,
      "name": "__htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void * __htab_map_lookup_elem(struct bpf_map * map, void * key)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
