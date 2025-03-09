# Function: <code>bpf_percpu_array_copy</code>

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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580449728,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:133",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449728,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506976,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:128",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506976,
      "name": "bpf_percpu_array_copy",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537008,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:156",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537008,
      "name": "bpf_percpu_array_copy",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580601424,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:200",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601424,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697120,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:205",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697120,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580769728,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:205",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769728,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854112,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854112,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580905152,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905152,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581051728,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:252",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051728,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063376,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:245",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063376,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078512,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:245",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078512,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306240,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:245",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306240,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581604832,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:265",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604832,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581987184,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:263",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987184,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178656,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:263",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178656,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582327072,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:263",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327072,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492235064,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492235064,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226130516,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226130516,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285460784,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285460784,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272381130,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272381130,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873952,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873952,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820080,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820080,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865200,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865200,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_percpu_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923712,
      "name": "bpf_percpu_array_copy",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:226",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923712,
      "name": "bpf_percpu_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int bpf_percpu_array_copy(struct bpf_map * map, void * key, void * value)
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
