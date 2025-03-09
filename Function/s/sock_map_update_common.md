# Function: <code>sock_map_update_common</code>

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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588225536,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:332",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588225536,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588564048,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:333",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564048,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781152,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:339",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781152,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589655008,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:467",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589655008,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589679648,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:468",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589679648,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589662912,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:466",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589662912,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590419136,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:466",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590419136,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592017056,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:466",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592017056,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593832704,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:468",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593832704,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594207232,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:464",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594207232,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595004608,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:464",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595004608,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502347352,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:339",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502347352,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235086336,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:339",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235086336,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295870416,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:339",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295870416,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278565864,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:339",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278565864,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588387536,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:339",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588387536,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588100224,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:339",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588100224,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588719712,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:339",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588719712,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_map_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588860112,
      "name": "sock_map_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:339",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_map_update",
        "net/core/sock_map.c:sock_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588860112,
      "name": "sock_map_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int sock_map_update_common(struct bpf_map * map, u32 idx, struct sock * sk, u64 flags)
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
