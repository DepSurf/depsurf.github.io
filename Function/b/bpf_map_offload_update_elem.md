# Function: <code>bpf_map_offload_update_elem</code>

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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580729328,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:372",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729328,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811552,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:411",
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
      "addr": 18446744071580811552,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580900544,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900544,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953808,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953808,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115040,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115040,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146672,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146672,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163440,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163440,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401600,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401600,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725376,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725376,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132640,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:444",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132640,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329168,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:585",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329168,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582490160,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490160,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492298832,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492298832,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226184272,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226184272,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285534912,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285534912,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272429018,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272429018,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922608,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922608,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868672,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868672,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580913856,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913856,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "bpf_map_offload_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973920,
      "name": "bpf_map_offload_update_elem",
      "external": true,
      "loc": "kernel/bpf/offload.c:447",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973920,
      "name": "bpf_map_offload_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bpf_map_offload_update_elem(struct bpf_map * map, void * key, void * value, u64 flags)
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
