# Function: <code>bpf_percpu_hash_copy</code>

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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580447824,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:746",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580447824,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505056,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1068",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505056,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534416,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1154",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534416,
      "name": "bpf_percpu_hash_copy",
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598224,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1188",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598224,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693504,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1210",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693504,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765840,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1247",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765840,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849792,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849792,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580900832,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900832,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045792,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1673",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045792,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056320,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1932",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056320,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071168,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1993",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071168,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298432,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2177",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298432,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595776,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2242",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595776,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976576,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2273",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976576,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582167936,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2326",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167936,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316592,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2348",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316592,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492229224,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492229224,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226125464,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226125464,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285453824,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285453824,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272376150,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272376150,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869632,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869632,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580815760,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580815760,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860880,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860880,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_hash_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919248,
      "name": "bpf_percpu_hash_copy",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1283",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919248,
      "name": "bpf_percpu_hash_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int bpf_percpu_hash_copy(struct bpf_map * map, void * key, void * value)
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
