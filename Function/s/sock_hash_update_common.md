# Function: <code>sock_hash_update_common</code>

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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588226384,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:651",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588226384,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588562560,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:655",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588562560,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588779648,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:663",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779648,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589656208,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:841",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656208,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 810
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589680432,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:982",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680432,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589661856,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:974",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589661856,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590419792,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:965",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590419792,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 817
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592017840,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:967",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592017840,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593833520,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:969",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593833520,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594208080,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:974",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594208080,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595005504,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:978",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595005504,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502348464,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:663",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502348464,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235087372,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:663",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235087372,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295872096,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:663",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295872096,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1536
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278567188,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:663",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278567188,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588386032,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:663",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588386032,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588098720,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:663",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098720,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588718208,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:663",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588718208,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
```

```json
{
  "name": "sock_hash_update_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588858608,
      "name": "sock_hash_update_common",
      "external": false,
      "loc": "net/core/sock_map.c:663",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_sock_hash_update",
        "net/core/sock_map.c:sock_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588858608,
      "name": "sock_hash_update_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
int sock_hash_update_common(struct bpf_map * map, void * key, struct sock * sk, u64 flags)
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
