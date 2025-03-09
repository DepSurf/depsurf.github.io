# Function: <code>bpf_fd_reuseport_array_lookup_elem</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821872,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:184",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821872,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916464,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916464,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969920,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969920,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135248,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:184",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135248,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169328,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:174",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169328,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581187792,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:174",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187792,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427808,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:174",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427808,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581754160,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:171",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754160,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582169808,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:168",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169808,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582366784,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:165",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366784,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582533840,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:165",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582533840,
      "name": "bpf_fd_reuseport_array_lookup_elem",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492320408,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492320408,
      "name": "bpf_fd_reuseport_array_lookup_elem",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226204632,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226204632,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285559888,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285559888,
      "name": "bpf_fd_reuseport_array_lookup_elem",
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272445206,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272445206,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938720,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938720,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884784,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884784,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929968,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929968,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```

```json
{
  "name": "bpf_fd_reuseport_array_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990560,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/reuseport_array.c:181",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990560,
      "name": "bpf_fd_reuseport_array_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map * map, void * key, void * value)
```
</details>
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
