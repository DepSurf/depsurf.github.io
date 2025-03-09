# Function: <code>tcp_set_window_clamp</code>

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
int tcp_set_window_clamp(struct sock * sk, int val)
```

```json
{
  "name": "tcp_set_window_clamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590090353,
      "name": "tcp_set_window_clamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:3278",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590092976,
      "name": "tcp_set_window_clamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int tcp_set_window_clamp(struct sock * sk, int val)
```

```json
{
  "name": "tcp_set_window_clamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590004988,
      "name": "tcp_set_window_clamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:3332",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590007616,
      "name": "tcp_set_window_clamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int tcp_set_window_clamp(struct sock * sk, int val)
```

```json
{
  "name": "tcp_set_window_clamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590775604,
      "name": "tcp_set_window_clamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:3356",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590778496,
      "name": "tcp_set_window_clamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int tcp_set_window_clamp(struct sock * sk, int val)
```

```json
{
  "name": "tcp_set_window_clamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592408765,
      "name": "tcp_set_window_clamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:3374",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:_bpf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592411280,
      "name": "tcp_set_window_clamp",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_set_window_clamp(struct sock * sk, int val)
```

```json
{
  "name": "tcp_set_window_clamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594256982,
      "name": "tcp_set_window_clamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:3473",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594255856,
      "name": "tcp_set_window_clamp",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_set_window_clamp(struct sock * sk, int val)
```

```json
{
  "name": "tcp_set_window_clamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594644869,
      "name": "tcp_set_window_clamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:3367",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594642672,
      "name": "tcp_set_window_clamp",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int tcp_set_window_clamp(struct sock * sk, int val)
```

```json
{
  "name": "tcp_set_window_clamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595445968,
      "name": "tcp_set_window_clamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:3372",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595445968,
      "name": "tcp_set_window_clamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int tcp_set_window_clamp(struct sock * sk, int val)
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
