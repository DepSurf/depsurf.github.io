# Function: <code>sock_bindtoindex</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_bindtoindex(struct sock * sk, int ifindex, bool lock_sk)
```

```json
{
  "name": "sock_bindtoindex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589235855,
      "name": "sock_bindtoindex",
      "external": true,
      "loc": "net/core/sock.c:597",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589232992,
      "name": "sock_bindtoindex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_bindtoindex(struct sock * sk, int ifindex, bool lock_sk)
```

```json
{
  "name": "sock_bindtoindex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589235244,
      "name": "sock_bindtoindex",
      "external": true,
      "loc": "net/core/sock.c:587",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589232080,
      "name": "sock_bindtoindex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_bindtoindex(struct sock * sk, int ifindex, bool lock_sk)
```

```json
{
  "name": "sock_bindtoindex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589129112,
      "name": "sock_bindtoindex",
      "external": true,
      "loc": "net/core/sock.c:595",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125536,
      "name": "sock_bindtoindex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_bindtoindex(struct sock * sk, int ifindex, bool lock_sk)
```

```json
{
  "name": "sock_bindtoindex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589849066,
      "name": "sock_bindtoindex",
      "external": true,
      "loc": "net/core/sock.c:614",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589844352,
      "name": "sock_bindtoindex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_bindtoindex(struct sock * sk, int ifindex, bool lock_sk)
```

```json
{
  "name": "sock_bindtoindex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591369276,
      "name": "sock_bindtoindex",
      "external": true,
      "loc": "net/core/sock.c:653",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591365648,
      "name": "sock_bindtoindex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int sock_bindtoindex(struct sock * sk, int ifindex, bool lock_sk)
```

```json
{
  "name": "sock_bindtoindex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593120496,
      "name": "sock_bindtoindex",
      "external": true,
      "loc": "net/core/sock.c:653",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593120496,
      "name": "sock_bindtoindex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int sock_bindtoindex(struct sock * sk, int ifindex, bool lock_sk)
```

```json
{
  "name": "sock_bindtoindex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593573184,
      "name": "sock_bindtoindex",
      "external": true,
      "loc": "net/core/sock.c:659",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593573184,
      "name": "sock_bindtoindex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int sock_bindtoindex(struct sock * sk, int ifindex, bool lock_sk)
```

```json
{
  "name": "sock_bindtoindex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594345824,
      "name": "sock_bindtoindex",
      "external": true,
      "loc": "net/core/sock.c:656",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594345824,
      "name": "sock_bindtoindex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int sock_bindtoindex(struct sock * sk, int ifindex, bool lock_sk)
```
</details>
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
