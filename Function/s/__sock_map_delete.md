# Function: <code>__sock_map_delete</code>

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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588224192,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:280",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588224192,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588561248,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:277",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588561248,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588778320,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:283",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588778320,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589653194,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:409",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_delete_elem"
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
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589677738,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:410",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_delete_elem"
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
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589660362,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:410",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_delete_elem"
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
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590416984,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:410",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_delete_elem"
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
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592014568,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:410",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_delete_elem"
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
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593829704,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:412",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_delete_elem"
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
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594204244,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:408",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_delete_elem"
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
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595001620,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:408",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_delete_elem"
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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502346040,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:283",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502346040,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235084532,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:283",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235084532,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295867920,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:283",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295867920,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278571658,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:283",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588384704,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:283",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384704,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588097392,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:283",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097392,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588716880,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:283",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588716880,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```

```json
{
  "name": "__sock_map_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588857200,
      "name": "__sock_map_delete",
      "external": false,
      "loc": "net/core/sock_map.c:283",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588857200,
      "name": "__sock_map_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __sock_map_delete(struct bpf_stab * stab, struct sock * sk_test, struct sock * * psk)
```
</details>
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
