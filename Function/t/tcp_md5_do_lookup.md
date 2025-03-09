# Function: <code>tcp_md5_do_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687584,
      "name": "tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:875",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_del",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687584,
      "name": "tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587134944,
      "name": "tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:884",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_del",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587134944,
      "name": "tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587333360,
      "name": "tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:890",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_del",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333360,
      "name": "tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587465712,
      "name": "tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:904",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587465712,
      "name": "tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587987776,
      "name": "tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:908",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587987776,
      "name": "tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588346064,
      "name": "tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:970",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588346064,
      "name": "tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588537836,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1564",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589110247,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1564",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588948544,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1566",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589563908,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1566",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589172773,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589788020,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590143257,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1616",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590811780,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1616",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590197314,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1630",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590871795,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1630",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590111453,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1634",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590801980,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1634",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590888461,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1628",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591620149,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1628",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592377482,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1675",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_inbound_md5_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592526662,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1675",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593312805,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1675",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594227055,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1695",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_inbound_md5_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594384774,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1695",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595217719,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1695",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594613903,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1708",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_inbound_md5_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594773076,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1708",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595613698,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1708",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595422533,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1799",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_inbound_md5_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595583844,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1799",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595977171,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1799",
      "file": "net/ipv4/tcp_ao.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ao.c:tcp_ao_add_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596461223,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1799",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502791168,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503493440,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235499312,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3236148832,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296432880,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297284832,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278904810,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279467322,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588779157,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589392388,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588491093,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117380,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589215333,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589829252,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
  "name": "tcp_md5_do_lookup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589256581,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589880439,
      "name": "tcp_md5_do_lookup",
      "external": false,
      "loc": "include/net/tcp.h:1588",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct tcp_md5sig_key * tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```
</details>
</li>
</ul>
