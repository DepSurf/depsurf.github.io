# Function: <code>bpf_map_offload_get_next_key</code>

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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580729552,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:403",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729552,
      "name": "bpf_map_offload_get_next_key",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811776,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:442",
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
      "addr": 18446744071580811776,
      "name": "bpf_map_offload_get_next_key",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580900800,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 18446744071580900800,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954064,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 18446744071580954064,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115296,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115296,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146928,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146928,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163696,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163696,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401856,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401856,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725664,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725664,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132960,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:475",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132960,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329488,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:616",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329488,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582490480,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:626",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_get_next_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490480,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492299128,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 18446603336492299128,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226184528,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 3226184528,
      "name": "bpf_map_offload_get_next_key",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285535344,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 13835058055285535344,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272429230,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 18446743936272429230,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922864,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 18446744071580922864,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868928,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 18446744071580868928,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914112,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 18446744071580914112,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "bpf_map_offload_get_next_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974176,
      "name": "bpf_map_offload_get_next_key",
      "external": true,
      "loc": "kernel/bpf/offload.c:478",
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
      "addr": 18446744071580974176,
      "name": "bpf_map_offload_get_next_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bpf_map_offload_get_next_key(struct bpf_map * map, void * key, void * next_key)
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
