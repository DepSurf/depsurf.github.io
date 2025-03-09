# Function: <code>bpf_fd_htab_map_lookup_elem</code>

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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534704,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1251",
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
      "addr": 18446744071580534704,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598512,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1285",
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
      "addr": 18446744071580598512,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693792,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1309",
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
      "addr": 18446744071580693792,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766128,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1377",
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
      "addr": 18446744071580766128,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850048,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 18446744071580850048,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901088,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 18446744071580901088,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046096,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1805",
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
      "addr": 18446744071581046096,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056672,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2074",
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
      "addr": 18446744071581056672,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071520,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2139",
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
      "addr": 18446744071581071520,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298832,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2325",
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
      "addr": 18446744071581298832,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596288,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2388",
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
      "addr": 18446744071581596288,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977120,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2419",
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
      "addr": 18446744071581977120,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168656,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2474",
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
      "addr": 18446744071582168656,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317328,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2496",
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
      "addr": 18446744071582317328,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492229624,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 18446603336492229624,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226125756,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 3226125756,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285454304,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 13835058055285454304,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272376512,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 18446743936272376512,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869888,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 18446744071580869888,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816016,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 18446744071580816016,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861136,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 18446744071580861136,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
```

```json
{
  "name": "bpf_fd_htab_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919584,
      "name": "bpf_fd_htab_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1413",
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
      "addr": 18446744071580919584,
      "name": "bpf_fd_htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int bpf_fd_htab_map_lookup_elem(struct bpf_map * map, void * key, u32 * value)
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
