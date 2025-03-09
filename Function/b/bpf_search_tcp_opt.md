# Function: <code>bpf_search_tcp_opt</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
const u8 * bpf_search_tcp_opt(const u8 * op, const u8 * opend, u8 search_kind, const u8 * magic, u8 magic_len, bool * eol)
```

```json
{
  "name": "bpf_search_tcp_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589507840,
      "name": "bpf_search_tcp_opt",
      "external": false,
      "loc": "net/core/filter.c:6642",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_store_hdr_opt",
        "net/core/filter.c:bpf_sock_ops_load_hdr_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507840,
      "name": "bpf_search_tcp_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
const u8 * bpf_search_tcp_opt(const u8 * op, const u8 * opend, u8 search_kind, const u8 * magic, u8 magic_len, bool * eol)
```

```json
{
  "name": "bpf_search_tcp_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589406240,
      "name": "bpf_search_tcp_opt",
      "external": false,
      "loc": "net/core/filter.c:6744",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_store_hdr_opt",
        "net/core/filter.c:bpf_sock_ops_load_hdr_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589406240,
      "name": "bpf_search_tcp_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
const u8 * bpf_search_tcp_opt(const u8 * op, const u8 * opend, u8 search_kind, const u8 * magic, u8 magic_len, bool * eol)
```

```json
{
  "name": "bpf_search_tcp_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590130416,
      "name": "bpf_search_tcp_opt",
      "external": false,
      "loc": "net/core/filter.c:6868",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_store_hdr_opt",
        "net/core/filter.c:bpf_sock_ops_load_hdr_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130416,
      "name": "bpf_search_tcp_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
const u8 * bpf_search_tcp_opt(const u8 * op, const u8 * opend, u8 search_kind, const u8 * magic, u8 magic_len, bool * eol)
```

```json
{
  "name": "bpf_search_tcp_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591682288,
      "name": "bpf_search_tcp_opt",
      "external": false,
      "loc": "net/core/filter.c:7207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_store_hdr_opt",
        "net/core/filter.c:bpf_sock_ops_load_hdr_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591682288,
      "name": "bpf_search_tcp_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
const u8 * bpf_search_tcp_opt(const u8 * op, const u8 * opend, u8 search_kind, const u8 * magic, u8 magic_len, bool * eol)
```

```json
{
  "name": "bpf_search_tcp_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593468720,
      "name": "bpf_search_tcp_opt",
      "external": false,
      "loc": "net/core/filter.c:7219",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_store_hdr_opt",
        "net/core/filter.c:bpf_sock_ops_load_hdr_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593468720,
      "name": "bpf_search_tcp_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
const u8 * bpf_search_tcp_opt(const u8 * op, const u8 * opend, u8 search_kind, const u8 * magic, u8 magic_len, bool * eol)
```

```json
{
  "name": "bpf_search_tcp_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593935552,
      "name": "bpf_search_tcp_opt",
      "external": false,
      "loc": "net/core/filter.c:7377",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_store_hdr_opt",
        "net/core/filter.c:bpf_sock_ops_load_hdr_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593935552,
      "name": "bpf_search_tcp_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
const u8 * bpf_search_tcp_opt(const u8 * op, const u8 * opend, u8 search_kind, const u8 * magic, u8 magic_len, bool * eol)
```

```json
{
  "name": "bpf_search_tcp_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594718320,
      "name": "bpf_search_tcp_opt",
      "external": false,
      "loc": "net/core/filter.c:7462",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_store_hdr_opt",
        "net/core/filter.c:bpf_sock_ops_load_hdr_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594718320,
      "name": "bpf_search_tcp_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
const u8 * bpf_search_tcp_opt(const u8 * op, const u8 * opend, u8 search_kind, const u8 * magic, u8 magic_len, bool * eol)
```
</details>
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
