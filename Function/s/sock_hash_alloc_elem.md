# Function: <code>sock_hash_alloc_elem</code>

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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588227100,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:625",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588563295,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:629",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588780383,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:637",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_alloc_elem(struct bpf_htab * htab, void * key, u32 key_size, u32 hash, struct sock * sk, struct bpf_htab_elem * old)
```

```json
{
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589649280,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:815",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589649280,
      "name": "sock_hash_alloc_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct bpf_shtab_elem * sock_hash_alloc_elem(struct bpf_shtab * htab, void * key, u32 key_size, u32 hash, struct sock * sk, struct bpf_shtab_elem * old)
```

```json
{
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589673184,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:955",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589673184,
      "name": "sock_hash_alloc_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589662188,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:947",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590420121,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:938",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592018194,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:940",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_shtab_elem * sock_hash_alloc_elem(struct bpf_shtab * htab, void * key, u32 key_size, u32 hash, struct sock * sk, struct bpf_shtab_elem * old)
```

```json
{
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593824928,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:942",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593824928,
      "name": "sock_hash_alloc_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
struct bpf_shtab_elem * sock_hash_alloc_elem(struct bpf_shtab * htab, void * key, u32 key_size, u32 hash, struct sock * sk, struct bpf_shtab_elem * old)
```

```json
{
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594199488,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:947",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594199488,
      "name": "sock_hash_alloc_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
struct bpf_shtab_elem * sock_hash_alloc_elem(struct bpf_shtab * htab, void * key, u32 key_size, u32 hash, struct sock * sk, struct bpf_shtab_elem * old)
```

```json
{
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594996704,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:951",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594996704,
      "name": "sock_hash_alloc_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502349312,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:637",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235088088,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:637",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295872924,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:637",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278567932,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:637",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588386767,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:637",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588099455,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:637",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588718943,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:637",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
  "name": "sock_hash_alloc_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588859343,
      "name": "sock_hash_alloc_elem",
      "external": false,
      "loc": "net/core/sock_map.c:637",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct bpf_htab_elem * sock_hash_alloc_elem(struct bpf_htab * htab, void * key, u32 key_size, u32 hash, struct sock * sk, struct bpf_htab_elem * old)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_htab * htab</code> ➡️ <code>struct bpf_shtab * htab</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct bpf_htab_elem * old</code> ➡️ <code>struct bpf_shtab_elem * old</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct bpf_htab_elem *</code> ➡️ <code>struct bpf_shtab_elem *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct bpf_shtab_elem * sock_hash_alloc_elem(struct bpf_shtab * htab, void * key, u32 key_size, u32 hash, struct sock * sk, struct bpf_shtab_elem * old)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct bpf_shtab_elem * sock_hash_alloc_elem(struct bpf_shtab * htab, void * key, u32 key_size, u32 hash, struct sock * sk, struct bpf_shtab_elem * old)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
