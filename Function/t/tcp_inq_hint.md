# Function: <code>tcp_inq_hint</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588246420,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1895",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588436475,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1904",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588845019,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1915",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589071427,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1916",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_inq_hint(struct sock * sk)
```

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590021872,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1986",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590021872,
      "name": "tcp_inq_hint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int tcp_inq_hint(struct sock * sk)
```

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590064032,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:2225",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590064032,
      "name": "tcp_inq_hint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int tcp_inq_hint(struct sock * sk)
```

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589978624,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:2268",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589978624,
      "name": "tcp_inq_hint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int tcp_inq_hint(struct sock * sk)
```

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590746960,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:2268",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590746960,
      "name": "tcp_inq_hint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int tcp_inq_hint(struct sock * sk)
```

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592378128,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:2295",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592378128,
      "name": "tcp_inq_hint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int tcp_inq_hint(struct sock * sk)
```

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594232192,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:2395",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594232192,
      "name": "tcp_inq_hint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int tcp_inq_hint(struct sock * sk)
```

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594619312,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:2281",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594619312,
      "name": "tcp_inq_hint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_inq_hint(struct sock * sk)
```

```json
{
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595421312,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:2288",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595421312,
      "name": "tcp_inq_hint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502677132,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1916",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235381460,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1916",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296286768,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1916",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278816740,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1916",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588677811,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1916",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588389795,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1916",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589113987,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1916",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_inq_hint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589153811,
      "name": "tcp_inq_hint",
      "external": false,
      "loc": "net/ipv4/tcp.c:1916",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
int tcp_inq_hint(struct sock * sk)
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
