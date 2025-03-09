# Function: <code>bpf_lru_init</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580511680,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:646",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511680,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541264,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:648",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541264,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605792,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:648",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605792,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701392,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:648",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701392,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774096,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:648",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774096,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858560,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858560,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909600,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909600,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056416,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056416,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068576,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:646",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068576,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581083568,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:646",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083568,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312192,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:646",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312192,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581611424,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:646",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611424,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995296,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:646",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995296,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582186608,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:651",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186608,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582335376,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:651",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335376,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492241424,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492241424,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226135640,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226135640,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285468448,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285468448,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272385738,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272385738,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878400,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878400,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824464,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824464,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869648,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869648,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```

```json
{
  "name": "bpf_lru_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928224,
      "name": "bpf_lru_init",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:645",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928224,
      "name": "bpf_lru_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int bpf_lru_init(struct bpf_lru * lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void * del_arg)
```
</details>
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
