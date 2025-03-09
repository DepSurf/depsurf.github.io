# Function: <code>bpf_map_meta_free</code>

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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543792,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:54",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543792,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580608960,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:54",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608960,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705136,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:54",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705136,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777568,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:69",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777568,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861936,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861936,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580912976,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912976,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059920,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059920,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072000,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:66",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072000,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086976,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:66",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086976,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315824,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315824,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615328,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:73",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615328,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999440,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:100",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999440,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582190832,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:90",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582190832,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582339664,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:90",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582339664,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492245624,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492245624,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226139120,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226139120,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285473424,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285473424,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272389152,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272389152,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881776,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881776,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580827840,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827840,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873024,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873024,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
```

```json
{
  "name": "bpf_map_meta_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931600,
      "name": "bpf_map_meta_free",
      "external": true,
      "loc": "kernel/bpf/map_in_map.c:72",
      "file": "kernel/bpf/map_in_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_free",
        "kernel/bpf/hashtab.c:htab_of_map_alloc",
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:array_of_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931600,
      "name": "bpf_map_meta_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_meta_free(struct bpf_map * map_meta)
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
