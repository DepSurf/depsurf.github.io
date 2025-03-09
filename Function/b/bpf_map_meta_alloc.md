# Function: <code>bpf_map_meta_alloc</code>

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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543552,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:12",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543552,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580608720,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:12",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608720,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580704912,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:12",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704912,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777296,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:12",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777296,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861632,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861632,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580912672,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912672,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059600,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059600,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071648,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071648,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086624,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086624,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:10",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592186560,
      "name": "bpf_map_meta_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581315408,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:10",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593960854,
      "name": "bpf_map_meta_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581614912,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:10",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596021481,
      "name": "bpf_map_meta_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581998992,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:10",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596543116,
      "name": "bpf_map_meta_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582190384,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:10",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597446209,
      "name": "bpf_map_meta_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582339216,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492245296,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492245296,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226138720,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226138720,
      "name": "bpf_map_meta_alloc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285472912,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285472912,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272388882,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272388882,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881472,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881472,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580827536,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827536,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580872720,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580872720,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
```

```json
{
  "name": "bpf_map_meta_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931296,
      "name": "bpf_map_meta_alloc",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:9",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931296,
      "name": "bpf_map_meta_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct bpf_map * bpf_map_meta_alloc(int inner_map_ufd)
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
