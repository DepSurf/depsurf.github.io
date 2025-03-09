# Function: <code>alloc_htab_elem</code>

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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, bool old_elem_exists)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442480,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:423",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442480,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, bool old_elem_exists)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580497232,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:573",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497232,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580526448,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:670",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526448,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589920,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:702",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589920,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685568,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:716",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685568,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757344,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:730",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757344,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841168,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841168,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580892208,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892208,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040048,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:830",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040048,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581048608,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:877",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048608,
      "name": "alloc_htab_elem",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062896,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:877",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062896,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296576,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:919",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296576,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593888,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:938",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593888,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:965",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964560,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071596021236,
      "name": "alloc_htab_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:977",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154000,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
    },
    {
      "addr": 18446744071596542863,
      "name": "alloc_htab_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:994",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303184,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
    },
    {
      "addr": 18446744071597445967,
      "name": "alloc_htab_elem.cold",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492221112,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492221112,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226117032,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226117032,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285441840,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285441840,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272366326,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272366326,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861008,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861008,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580807136,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807136,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852256,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852256,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem * old_elem)
```

```json
{
  "name": "alloc_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580910592,
      "name": "alloc_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:721",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910592,
      "name": "alloc_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
struct htab_elem * alloc_htab_elem(struct bpf_htab * htab, void * key, void * value, u32 key_size, u32 hash, bool percpu, bool onallcpus, bool old_elem_exists)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct htab_elem * old_elem</code>
</li>
<li>
<b>Param removed. </b>
<code>bool old_elem_exists</code>
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
