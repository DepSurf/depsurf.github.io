# Function: <code>ipv4_rcv_saddr_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ipv4_rcv_saddr_equal(const struct sock * sk1, const struct sock * sk2)
```

```json
{
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586733504,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/udp.c:312",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586733504,
      "name": "ipv4_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ipv4_rcv_saddr_equal(const struct sock * sk1, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587186112,
      "name": "ipv4_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/udp.c:362",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587186112,
      "name": "ipv4_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ipv4_rcv_saddr_equal(const struct sock * sk1, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587387024,
      "name": "ipv4_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/udp.c:363",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587387024,
      "name": "ipv4_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587369941,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:85",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587889566,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:85",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588235067,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:80",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588422817,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:80",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588826212,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589050071,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590016457,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:78",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590059102,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:78",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589973709,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:78",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590743045,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:78",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592373833,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:78",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594222539,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:78",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594609637,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:78",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595413306,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:78",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502666140,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235368864,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296270220,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278801002,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588656455,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588368439,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589092631,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "ipv4_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589132281,
      "name": "ipv4_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:76",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool match_wildcard</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int ipv4_rcv_saddr_equal(const struct sock * sk1, const struct sock * sk2, bool match_wildcard)
```
</details>
</li>
</ul>
