# Function: <code>bpf_map_offload_delete_elem</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580729456,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:390",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729456,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811680,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:429",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811680,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580900688,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900688,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953952,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953952,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115184,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115184,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146816,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146816,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163584,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163584,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401744,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401744,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725552,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725552,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132832,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:462",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132832,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329360,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:603",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329360,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582490352,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:613",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490352,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492299008,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492299008,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226184424,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226184424,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285535168,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285535168,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272429138,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272429138,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922752,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922752,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868816,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868816,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914000,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914000,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "bpf_map_offload_delete_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974064,
      "name": "bpf_map_offload_delete_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:465",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974064,
      "name": "bpf_map_offload_delete_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map * map, void * key)
```
</details>
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
