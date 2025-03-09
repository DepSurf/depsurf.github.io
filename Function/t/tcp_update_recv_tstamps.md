# Function: <code>tcp_update_recv_tstamps</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587913192,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1719",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588247135,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588437198,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1849",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588845962,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1839",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589072384,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590033245,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1906",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590078072,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:2145",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void tcp_update_recv_tstamps(struct sk_buff * skb, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589975264,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1744",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589975264,
      "name": "tcp_update_recv_tstamps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void tcp_update_recv_tstamps(struct sk_buff * skb, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590760672,
      "name": "tcp_update_recv_tstamps",
      "external": true,
      "loc": "net/ipv4/tcp.c:1743",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590760672,
      "name": "tcp_update_recv_tstamps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void tcp_update_recv_tstamps(struct sk_buff * skb, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592393424,
      "name": "tcp_update_recv_tstamps",
      "external": true,
      "loc": "net/ipv4/tcp.c:1771",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592393424,
      "name": "tcp_update_recv_tstamps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void tcp_update_recv_tstamps(struct sk_buff * skb, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594244480,
      "name": "tcp_update_recv_tstamps",
      "external": true,
      "loc": "net/ipv4/tcp.c:1871",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594244480,
      "name": "tcp_update_recv_tstamps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void tcp_update_recv_tstamps(struct sk_buff * skb, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594630608,
      "name": "tcp_update_recv_tstamps",
      "external": true,
      "loc": "net/ipv4/tcp.c:1727",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594630608,
      "name": "tcp_update_recv_tstamps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void tcp_update_recv_tstamps(struct sk_buff * skb, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595433696,
      "name": "tcp_update_recv_tstamps",
      "external": true,
      "loc": "net/ipv4/tcp.c:1729",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595433696,
      "name": "tcp_update_recv_tstamps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502677984,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235381956,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296287888,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278817238,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588678768,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588390752,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589114944,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
  "name": "tcp_update_recv_tstamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589154768,
      "name": "tcp_update_recv_tstamps",
      "external": false,
      "loc": "net/ipv4/tcp.c:1840",
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void tcp_update_recv_tstamps(struct sk_buff * skb, struct scm_timestamping_internal * tss)
```
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
