# Function: <code>__tcp_cleanup_rbuf</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __tcp_cleanup_rbuf(struct sock * sk, int copied)
```

```json
{
  "name": "__tcp_cleanup_rbuf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594224960,
      "name": "__tcp_cleanup_rbuf",
      "external": false,
      "loc": "net/ipv4/tcp.c:1571",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_read_skb",
        "net/ipv4/tcp.c:tcp_cleanup_rbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594224960,
      "name": "__tcp_cleanup_rbuf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void __tcp_cleanup_rbuf(struct sock * sk, int copied)
```

```json
{
  "name": "__tcp_cleanup_rbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594628064,
      "name": "__tcp_cleanup_rbuf",
      "external": true,
      "loc": "net/ipv4/tcp.c:1436",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_eat_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594628064,
      "name": "__tcp_cleanup_rbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void __tcp_cleanup_rbuf(struct sock * sk, int copied)
```

```json
{
  "name": "__tcp_cleanup_rbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595431136,
      "name": "__tcp_cleanup_rbuf",
      "external": true,
      "loc": "net/ipv4/tcp.c:1444",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_eat_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595431136,
      "name": "__tcp_cleanup_rbuf",
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void __tcp_cleanup_rbuf(struct sock * sk, int copied)
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
