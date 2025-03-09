# Function: <code>inet_bhash2_reset_saddr</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void inet_bhash2_reset_saddr(struct sock * sk)
```

```json
{
  "name": "inet_bhash2_reset_saddr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594201024,
      "name": "inet_bhash2_reset_saddr",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:972",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594201024,
      "name": "inet_bhash2_reset_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void inet_bhash2_reset_saddr(struct sock * sk)
```

```json
{
  "name": "inet_bhash2_reset_saddr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594588048,
      "name": "inet_bhash2_reset_saddr",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:962",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594588048,
      "name": "inet_bhash2_reset_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void inet_bhash2_reset_saddr(struct sock * sk)
```

```json
{
  "name": "inet_bhash2_reset_saddr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595391520,
      "name": "inet_bhash2_reset_saddr",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:974",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595391520,
      "name": "inet_bhash2_reset_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void inet_bhash2_reset_saddr(struct sock * sk)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
