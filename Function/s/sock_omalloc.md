# Function: <code>sock_omalloc</code>

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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587421728,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:1944",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587421728,
      "name": "sock_omalloc",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587725824,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:1964",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587725824,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587858144,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:1960",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587858144,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588162720,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2101",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162720,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588368000,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2116",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368000,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589232544,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2225",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589232544,
      "name": "sock_omalloc",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589231216,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589231216,
      "name": "sock_omalloc",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589124672,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2240",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589124672,
      "name": "sock_omalloc",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589843536,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2364",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589843536,
      "name": "sock_omalloc",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591364720,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2531",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591364720,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593119264,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2610",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593119264,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593571952,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2670",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593571952,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594344544,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2650",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:msg_zerocopy_realloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594344544,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501877784,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2116",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501877784,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234641724,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2116",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234641724,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295284688,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2116",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295284688,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278199640,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2116",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278199640,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587974784,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2116",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974784,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587687888,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2116",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587687888,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588306560,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2116",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588306560,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```

```json
{
  "name": "sock_omalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588441776,
      "name": "sock_omalloc",
      "external": true,
      "loc": "net/core/sock.c:2116",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588441776,
      "name": "sock_omalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct sk_buff * sock_omalloc(struct sock * sk, long unsigned int size, gfp_t priority)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
