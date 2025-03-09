# Function: <code>tcp_tso_autosize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586670420,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1533",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587126809,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1548",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 tcp_tso_autosize(const struct sock * sk, unsigned int mss_now, int min_tso_segs)
```

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587305152,
      "name": "tcp_tso_autosize",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1583",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305152,
      "name": "tcp_tso_autosize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 tcp_tso_autosize(const struct sock * sk, unsigned int mss_now, int min_tso_segs)
```

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587436848,
      "name": "tcp_tso_autosize",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1664",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436848,
      "name": "tcp_tso_autosize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 tcp_tso_autosize(const struct sock * sk, unsigned int mss_now, int min_tso_segs)
```

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587957835,
      "name": "tcp_tso_autosize",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1718",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_tso_segs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587957728,
      "name": "tcp_tso_autosize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588317620,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1709",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588506621,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1697",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588921839,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1710",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589145743,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590115451,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1792",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590163175,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1960",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590077207,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1961",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590830928,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1961",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_tso_segs"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592466408,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1968",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_tso_segs"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594320904,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1970",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_tso_segs"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594707478,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1962",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_tso_segs"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595512086,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2005",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_tso_segs"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502761564,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235465824,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296391728,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278884462,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588752127,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588464079,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589188303,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
  "name": "tcp_tso_autosize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589228367,
      "name": "tcp_tso_autosize",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
u32 tcp_tso_autosize(const struct sock * sk, unsigned int mss_now, int min_tso_segs)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
u32 tcp_tso_autosize(const struct sock * sk, unsigned int mss_now, int min_tso_segs)
```
</details>
</li>
</ul>
