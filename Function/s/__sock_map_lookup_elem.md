# Function: <code>__sock_map_lookup_elem</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sock * __sock_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621568,
      "name": "__sock_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/sockmap.c:633",
      "file": "kernel/bpf/sockmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:do_sk_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621568,
      "name": "__sock_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct sock * __sock_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747200,
      "name": "__sock_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/sockmap.c:1776",
      "file": "kernel/bpf/sockmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_msg_redirect_map",
        "net/core/filter.c:bpf_sk_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747200,
      "name": "__sock_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588223720,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:264",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588560776,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:261",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588777848,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:267",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589651202,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:371",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map",
        "net/core/sock_map.c:sock_map_lookup"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589672660,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:372",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_seq_next",
        "net/core/sock_map.c:sock_map_seq_start",
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map",
        "net/core/sock_map.c:sock_map_lookup"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589655284,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:372",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_seq_next",
        "net/core/sock_map.c:sock_map_seq_start",
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map",
        "net/core/sock_map.c:sock_map_lookup"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590411988,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:372",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_seq_next",
        "net/core/sock_map.c:sock_map_seq_start",
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map",
        "net/core/sock_map.c:sock_map_lookup"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592009077,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:372",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_seq_next",
        "net/core/sock_map.c:sock_map_seq_start",
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map",
        "net/core/sock_map.c:sock_map_lookup"
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
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593823381,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:374",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_seq_next",
        "net/core/sock_map.c:sock_map_seq_start",
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map",
        "net/core/sock_map.c:sock_map_lookup"
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
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594197941,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:370",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_seq_next",
        "net/core/sock_map.c:sock_map_seq_start",
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map",
        "net/core/sock_map.c:sock_map_lookup"
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
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594994965,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:370",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_seq_next",
        "net/core/sock_map.c:sock_map_seq_start",
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map",
        "net/core/sock_map.c:sock_map_lookup"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502343588,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:267",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235084176,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:267",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295867276,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:267",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278568686,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:267",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588384232,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:267",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588096920,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:267",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588716408,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:267",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588856728,
      "name": "__sock_map_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:267",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:bpf_msg_redirect_map",
        "net/core/sock_map.c:bpf_sk_redirect_map"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct sock * __sock_map_lookup_elem(struct bpf_map * map, u32 key)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct sock * __sock_map_lookup_elem(struct bpf_map * map, u32 key)
```
</details>
</li>
</ul>
