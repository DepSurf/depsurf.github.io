# Function: <code>__sock_hash_lookup_elem</code>

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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747488,
      "name": "__sock_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/sockmap.c:2500",
      "file": "kernel/bpf/sockmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_msg_redirect_hash",
        "net/core/filter.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747488,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588227840,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:554",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227840,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588564960,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:558",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564960,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588782080,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:566",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588782080,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650032,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:744",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash",
        "net/core/sock_map.c:sock_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650032,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589674592,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:884",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash",
        "net/core/sock_map.c:sock_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674592,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589656944,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:876",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash",
        "net/core/sock_map.c:sock_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656944,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590413888,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:867",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash",
        "net/core/sock_map.c:sock_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590413888,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592011168,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:869",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash",
        "net/core/sock_map.c:sock_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592011168,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593826656,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:871",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash",
        "net/core/sock_map.c:sock_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593826656,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594201120,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:876",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash",
        "net/core/sock_map.c:sock_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594201120,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594998400,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:880",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash",
        "net/core/sock_map.c:sock_hash_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594998400,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502350344,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:566",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502350344,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235088936,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:566",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235088936,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295874496,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:566",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295874496,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278568972,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:566",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278568972,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588388464,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:566",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588388464,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588101152,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:566",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101152,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588720640,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:566",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588720640,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "__sock_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588861040,
      "name": "__sock_hash_lookup_elem",
      "external": false,
      "loc": "net/core/sock_map.c:566",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:bpf_msg_redirect_hash",
        "net/core/sock_map.c:bpf_sk_redirect_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588861040,
      "name": "__sock_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
struct sock * __sock_hash_lookup_elem(struct bpf_map * map, void * key)
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
