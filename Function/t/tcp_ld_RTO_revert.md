# Function: <code>tcp_ld_RTO_revert</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_ld_RTO_revert(struct sock * sk, u32 seq)
```

```json
{
  "name": "tcp_ld_RTO_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590149842,
      "name": "tcp_ld_RTO_revert",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:407",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590137728,
      "name": "tcp_ld_RTO_revert.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071590138080,
      "name": "tcp_ld_RTO_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_ld_RTO_revert(struct sock * sk, u32 seq)
```

```json
{
  "name": "tcp_ld_RTO_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590198578,
      "name": "tcp_ld_RTO_revert",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:408",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590185232,
      "name": "tcp_ld_RTO_revert.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071590185584,
      "name": "tcp_ld_RTO_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_ld_RTO_revert(struct sock * sk, u32 seq)
```

```json
{
  "name": "tcp_ld_RTO_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590112756,
      "name": "tcp_ld_RTO_revert",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:408",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590099440,
      "name": "tcp_ld_RTO_revert.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
    },
    {
      "addr": 18446744071590099792,
      "name": "tcp_ld_RTO_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void tcp_ld_RTO_revert(struct sock * sk, u32 seq)
```

```json
{
  "name": "tcp_ld_RTO_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590889780,
      "name": "tcp_ld_RTO_revert",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:408",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590874032,
      "name": "tcp_ld_RTO_revert.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071592719948,
      "name": "tcp_ld_RTO_revert.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071590874400,
      "name": "tcp_ld_RTO_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void tcp_ld_RTO_revert(struct sock * sk, u32 seq)
```

```json
{
  "name": "tcp_ld_RTO_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592528023,
      "name": "tcp_ld_RTO_revert",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:409",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592511952,
      "name": "tcp_ld_RTO_revert.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071594606380,
      "name": "tcp_ld_RTO_revert.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071592512352,
      "name": "tcp_ld_RTO_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void tcp_ld_RTO_revert(struct sock * sk, u32 seq)
```

```json
{
  "name": "tcp_ld_RTO_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594386124,
      "name": "tcp_ld_RTO_revert",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:418",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594367760,
      "name": "tcp_ld_RTO_revert.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071596341717,
      "name": "tcp_ld_RTO_revert.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071594368176,
      "name": "tcp_ld_RTO_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void tcp_ld_RTO_revert(struct sock * sk, u32 seq)
```

```json
{
  "name": "tcp_ld_RTO_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594774508,
      "name": "tcp_ld_RTO_revert",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:419",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594756064,
      "name": "tcp_ld_RTO_revert.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071596870993,
      "name": "tcp_ld_RTO_revert.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071594756496,
      "name": "tcp_ld_RTO_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void tcp_ld_RTO_revert(struct sock * sk, u32 seq)
```

```json
{
  "name": "tcp_ld_RTO_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595585350,
      "name": "tcp_ld_RTO_revert",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:421",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595562736,
      "name": "tcp_ld_RTO_revert.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071597794633,
      "name": "tcp_ld_RTO_revert.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071595563168,
      "name": "tcp_ld_RTO_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void tcp_ld_RTO_revert(struct sock * sk, u32 seq)
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
