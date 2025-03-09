# Function: <code>smack_from_netlbl</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct smack_known * smack_from_netlbl(const struct sock * sk, u16 family, struct sk_buff * skb)
```

```json
{
  "name": "smack_from_netlbl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584023632,
      "name": "smack_from_netlbl",
      "external": false,
      "loc": "security/smack/smack_lsm.c:3868",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584023632,
      "name": "smack_from_netlbl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
struct smack_known * smack_from_netlbl(const struct sock * sk, u16 family, struct sk_buff * skb)
```

```json
{
  "name": "smack_from_netlbl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584052176,
      "name": "smack_from_netlbl",
      "external": false,
      "loc": "security/smack/smack_lsm.c:3867",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584052176,
      "name": "smack_from_netlbl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct smack_known * smack_from_netlbl(const struct sock * sk, u16 family, struct sk_buff * skb)
```

```json
{
  "name": "smack_from_netlbl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584423792,
      "name": "smack_from_netlbl",
      "external": false,
      "loc": "security/smack/smack_lsm.c:3867",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584423792,
      "name": "smack_from_netlbl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct smack_known * smack_from_netlbl(const struct sock * sk, u16 family, struct sk_buff * skb)
```

```json
{
  "name": "smack_from_netlbl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585053024,
      "name": "smack_from_netlbl",
      "external": false,
      "loc": "security/smack/smack_lsm.c:3876",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053024,
      "name": "smack_from_netlbl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct smack_known * smack_from_netlbl(const struct sock * sk, u16 family, struct sk_buff * skb)
```

```json
{
  "name": "smack_from_netlbl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585772928,
      "name": "smack_from_netlbl",
      "external": false,
      "loc": "security/smack/smack_lsm.c:3944",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772928,
      "name": "smack_from_netlbl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
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
struct smack_known * smack_from_netlbl(const struct sock * sk, u16 family, struct sk_buff * skb)
```

```json
{
  "name": "smack_from_netlbl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586004368,
      "name": "smack_from_netlbl",
      "external": false,
      "loc": "security/smack/smack_lsm.c:4007",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586004368,
      "name": "smack_from_netlbl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
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
struct smack_known * smack_from_netlbl(const struct sock * sk, u16 family, struct sk_buff * skb)
```

```json
{
  "name": "smack_from_netlbl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_from_netlbl",
      "external": false,
      "loc": "security/smack/smack_lsm.c:4131",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586257440,
      "name": "smack_from_netlbl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
    },
    {
      "addr": 18446744071597526369,
      "name": "smack_from_netlbl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
struct smack_known * smack_from_netlbl(const struct sock * sk, u16 family, struct sk_buff * skb)
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
