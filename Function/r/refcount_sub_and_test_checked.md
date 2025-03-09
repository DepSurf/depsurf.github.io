# Function: <code>refcount_sub_and_test_checked</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583965664,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:177",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965664,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145520,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145520,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584267968,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267968,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496150632,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_wfree",
        "net/core/sock.c:sock_wfree",
        "net/core/sock.c:sock_wfree",
        "net/core/sock.c:sock_wfree",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496150632,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229472360,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_wfree",
        "net/core/sock.c:sock_wfree",
        "net/core/sock.c:sock_wfree",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229472360,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290411648,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290411648,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275204984,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275204984,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584236704,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236704,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584171904,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171904,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584220464,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220464,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
```

```json
{
  "name": "refcount_sub_and_test_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325296,
      "name": "refcount_sub_and_test_checked",
      "external": true,
      "loc": "lib/refcount.c:180",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325296,
      "name": "refcount_sub_and_test_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
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
bool refcount_sub_and_test_checked(unsigned int i, refcount_t * r)
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
