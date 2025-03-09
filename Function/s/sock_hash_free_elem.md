# Function: <code>sock_hash_free_elem</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588230206,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:570",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588560064,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:574",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588560064,
      "name": "sock_hash_free_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588777136,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:582",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777136,
      "name": "sock_hash_free_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589653111,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:760",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589677655,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:900",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589660279,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:892",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590416901,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:883",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592014485,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:885",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593829621,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:887",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594204165,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:892",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595001541,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:896",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502344632,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:582",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502344632,
      "name": "sock_hash_free_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235083360,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:582",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235083360,
      "name": "sock_hash_free_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295878076,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:582",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278571758,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:582",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
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
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588383520,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:582",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588383520,
      "name": "sock_hash_free_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588096208,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:582",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588096208,
      "name": "sock_hash_free_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588715696,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:582",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588715696,
      "name": "sock_hash_free_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```

```json
{
  "name": "sock_hash_free_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588856016,
      "name": "sock_hash_free_elem",
      "external": false,
      "loc": "net/core/sock_map.c:582",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588856016,
      "name": "sock_hash_free_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void sock_hash_free_elem(struct bpf_htab * htab, struct bpf_htab_elem * elem)
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
