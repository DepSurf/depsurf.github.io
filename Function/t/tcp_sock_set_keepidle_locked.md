# Function: <code>tcp_sock_set_keepidle_locked</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock * sk, int val)
```

```json
{
  "name": "tcp_sock_set_keepidle_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590089392,
      "name": "tcp_sock_set_keepidle_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:3221",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590089392,
      "name": "tcp_sock_set_keepidle_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int tcp_sock_set_keepidle_locked(struct sock * sk, int val)
```

```json
{
  "name": "tcp_sock_set_keepidle_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590004032,
      "name": "tcp_sock_set_keepidle_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:3275",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590004032,
      "name": "tcp_sock_set_keepidle_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock * sk, int val)
```

```json
{
  "name": "tcp_sock_set_keepidle_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590774644,
      "name": "tcp_sock_set_keepidle_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:3299",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592715957,
      "name": "tcp_sock_set_keepidle_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590774592,
      "name": "tcp_sock_set_keepidle_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock * sk, int val)
```

```json
{
  "name": "tcp_sock_set_keepidle_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sock_set_keepidle_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:3317",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594602223,
      "name": "tcp_sock_set_keepidle_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071592407552,
      "name": "tcp_sock_set_keepidle_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock * sk, int val)
```

```json
{
  "name": "tcp_sock_set_keepidle_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sock_set_keepidle_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:3416",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596337608,
      "name": "tcp_sock_set_keepidle_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071594255584,
      "name": "tcp_sock_set_keepidle_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock * sk, int val)
```

```json
{
  "name": "tcp_sock_set_keepidle_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sock_set_keepidle_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:3308",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596867174,
      "name": "tcp_sock_set_keepidle_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071594642384,
      "name": "tcp_sock_set_keepidle_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock * sk, int val)
```

```json
{
  "name": "tcp_sock_set_keepidle_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sock_set_keepidle_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:3317",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597792082,
      "name": "tcp_sock_set_keepidle_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071595445680,
      "name": "tcp_sock_set_keepidle_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int tcp_sock_set_keepidle_locked(struct sock * sk, int val)
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
