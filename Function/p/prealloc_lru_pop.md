# Function: <code>prealloc_lru_pop</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580503235,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:108",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525968,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:118",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525968,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589472,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:123",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589472,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685120,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:123",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685120,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756896,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:127",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756896,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840688,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840688,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891728,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891728,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037168,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:234",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037168,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046064,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:261",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046064,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581060912,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:261",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060912,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581292416,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:287",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292416,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582352,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:307",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582352,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960112,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:287",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960112,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148784,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:298",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148784,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582297840,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:302",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297840,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492219864,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492219864,
      "name": "prealloc_lru_pop",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226116596,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226116596,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285441040,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285441040,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272373932,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860528,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860528,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806656,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806656,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851776,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851776,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
```

```json
{
  "name": "prealloc_lru_pop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580910096,
      "name": "prealloc_lru_pop",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910096,
      "name": "prealloc_lru_pop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct htab_elem * prealloc_lru_pop(struct bpf_htab * htab, void * key, u32 hash)
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
