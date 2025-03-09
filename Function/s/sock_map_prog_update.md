# Function: <code>sock_map_prog_update</code>

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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588229792,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:966",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588229792,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566896,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:973",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566896,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588784016,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:993",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588784016,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, struct bpf_prog * old, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589657504,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:1243",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657504,
      "name": "sock_map_prog_update",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, struct bpf_prog * old, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589682096,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:1451",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682096,
      "name": "sock_map_prog_update",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, struct bpf_prog * old, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589655392,
      "name": "sock_map_prog_update",
      "external": false,
      "loc": "net/core/sock_map.c:1434",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589655392,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, struct bpf_prog * old, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590412096,
      "name": "sock_map_prog_update",
      "external": false,
      "loc": "net/core/sock_map.c:1425",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590412096,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592019566,
      "name": "sock_map_prog_update",
      "external": false,
      "loc": "net/core/sock_map.c:1469",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593835198,
      "name": "sock_map_prog_update",
      "external": false,
      "loc": "net/core/sock_map.c:1471",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594209758,
      "name": "sock_map_prog_update",
      "external": false,
      "loc": "net/core/sock_map.c:1485",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595007182,
      "name": "sock_map_prog_update",
      "external": false,
      "loc": "net/core/sock_map.c:1491",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502352544,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:993",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502352544,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235090664,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:993",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235090664,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295877232,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:993",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295877232,
      "name": "sock_map_prog_update",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278571240,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:993",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278571240,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390400,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:993",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390400,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588103088,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:993",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588103088,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588722576,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:993",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588722576,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
```

```json
{
  "name": "sock_map_prog_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588862976,
      "name": "sock_map_prog_update",
      "external": true,
      "loc": "net/core/sock_map.c:993",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862976,
      "name": "sock_map_prog_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, u32 which)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog * old</code>
</li>
<li>
<b>Param reordered. </b>
<code>map, prog, which</code> ➡️ <code>map, prog, old, which</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int sock_map_prog_update(struct bpf_map * map, struct bpf_prog * prog, struct bpf_prog * old, u32 which)
```
</details>
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
