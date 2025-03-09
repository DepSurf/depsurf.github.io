# Function: <code>__tcp_sock_set_quickack</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tcp_sock_set_quickack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590022920,
      "name": "__tcp_sock_set_quickack",
      "external": false,
      "loc": "net/ipv4/tcp.c:2918",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_quickack"
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
  "name": "__tcp_sock_set_quickack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590079672,
      "name": "__tcp_sock_set_quickack",
      "external": false,
      "loc": "net/ipv4/tcp.c:3176",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_quickack"
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
  "name": "__tcp_sock_set_quickack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589999464,
      "name": "__tcp_sock_set_quickack",
      "external": false,
      "loc": "net/ipv4/tcp.c:3230",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_quickack"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __tcp_sock_set_quickack(struct sock * sk, int val)
```

```json
{
  "name": "__tcp_sock_set_quickack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590760537,
      "name": "__tcp_sock_set_quickack",
      "external": false,
      "loc": "net/ipv4/tcp.c:3254",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_quickack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590760480,
      "name": "__tcp_sock_set_quickack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071592715474,
      "name": "__tcp_sock_set_quickack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __tcp_sock_set_quickack(struct sock * sk, int val)
```

```json
{
  "name": "__tcp_sock_set_quickack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592393273,
      "name": "__tcp_sock_set_quickack",
      "external": false,
      "loc": "net/ipv4/tcp.c:3272",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_quickack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592393216,
      "name": "__tcp_sock_set_quickack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071594601739,
      "name": "__tcp_sock_set_quickack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __tcp_sock_set_quickack(struct sock * sk, int val)
```

```json
{
  "name": "__tcp_sock_set_quickack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594244297,
      "name": "__tcp_sock_set_quickack",
      "external": false,
      "loc": "net/ipv4/tcp.c:3371",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594244240,
      "name": "__tcp_sock_set_quickack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071596337312,
      "name": "__tcp_sock_set_quickack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __tcp_sock_set_quickack(struct sock * sk, int val)
```

```json
{
  "name": "__tcp_sock_set_quickack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594630388,
      "name": "__tcp_sock_set_quickack",
      "external": false,
      "loc": "net/ipv4/tcp.c:3263",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594630336,
      "name": "__tcp_sock_set_quickack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071596866872,
      "name": "__tcp_sock_set_quickack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __tcp_sock_set_quickack(struct sock * sk, int val)
```

```json
{
  "name": "__tcp_sock_set_quickack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595433472,
      "name": "__tcp_sock_set_quickack",
      "external": false,
      "loc": "net/ipv4/tcp.c:3269",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595433424,
      "name": "__tcp_sock_set_quickack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071597791780,
      "name": "__tcp_sock_set_quickack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void __tcp_sock_set_quickack(struct sock * sk, int val)
```
</details>
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
