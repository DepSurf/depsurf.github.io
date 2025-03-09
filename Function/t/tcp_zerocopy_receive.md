# Function: <code>tcp_zerocopy_receive</code>

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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588248846,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1751",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588432469,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1747",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588839024,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1737",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589065337,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int tcp_zerocopy_receive(struct sock * sk, struct tcp_zerocopy_receive * zc)
```

```json
{
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590025552,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1775",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590025552,
      "name": "tcp_zerocopy_receive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1650
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
int tcp_zerocopy_receive(struct sock * sk, struct tcp_zerocopy_receive * zc)
```

```json
{
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590079792,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:2008",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590079792,
      "name": "tcp_zerocopy_receive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1964
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
int tcp_zerocopy_receive(struct sock * sk, struct tcp_zerocopy_receive * zc, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589994272,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:2059",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589994272,
      "name": "tcp_zerocopy_receive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1955
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_zerocopy_receive(struct sock * sk, struct tcp_zerocopy_receive * zc, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:2059",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590763744,
      "name": "tcp_zerocopy_receive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2043
    },
    {
      "addr": 18446744071592715660,
      "name": "tcp_zerocopy_receive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int tcp_zerocopy_receive(struct sock * sk, struct tcp_zerocopy_receive * zc, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:2086",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396464,
      "name": "tcp_zerocopy_receive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2010
    },
    {
      "addr": 18446744071594601907,
      "name": "tcp_zerocopy_receive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int tcp_zerocopy_receive(struct sock * sk, struct tcp_zerocopy_receive * zc, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:2186",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594247616,
      "name": "tcp_zerocopy_receive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1996
    },
    {
      "addr": 18446744071596337441,
      "name": "tcp_zerocopy_receive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int tcp_zerocopy_receive(struct sock * sk, struct tcp_zerocopy_receive * zc, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:2070",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594633840,
      "name": "tcp_zerocopy_receive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2451
    },
    {
      "addr": 18446744071596867000,
      "name": "tcp_zerocopy_receive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int tcp_zerocopy_receive(struct sock * sk, struct tcp_zerocopy_receive * zc, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:2077",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595437024,
      "name": "tcp_zerocopy_receive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2581
    },
    {
      "addr": 18446744071597791908,
      "name": "tcp_zerocopy_receive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502687372,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235389004,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296290996,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278812086,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588671721,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588383705,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589107897,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tcp_zerocopy_receive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589147657,
      "name": "tcp_zerocopy_receive",
      "external": false,
      "loc": "net/ipv4/tcp.c:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int tcp_zerocopy_receive(struct sock * sk, struct tcp_zerocopy_receive * zc)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scm_timestamping_internal * tss</code>
</li>
</ul>
</details>
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
