# Function: <code>tcp_time_stamp_raw</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587378545,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:737",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587482965,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:737",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587684429,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:737",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587990654,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:737",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587899811,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:713",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588004983,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:713",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588211165,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:713",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588526912,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:713",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588249679,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:723",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588355686,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:723",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588565733,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:723",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892066,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:723",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588432028,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:750",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588546103,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:750",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588763269,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:750",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589115534,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:750",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588838758,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:751",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588957057,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:751",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589196197,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:751",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589568790,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:751",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589061374,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589181569,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589421621,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589792945,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590029251,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:783",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590152533,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:783",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590814885,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:783",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590082469,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:789",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590201589,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:789",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590875054,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:789",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589996963,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:794",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590115755,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:794",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590804216,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:794",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590767438,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:787",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590892824,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:787",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591622431,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:787",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592400750,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:801",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592531042,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:801",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593315098,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:801",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594262424,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:814",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594389160,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:814",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595220013,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:814",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594649870,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:809",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594777506,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:809",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595616099,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:809",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502682912,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502799372,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503074560,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503497056,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 tcp_time_stamp_raw()
```

```json
{
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235377284,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235496268,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    },
    {
      "addr": 3235757452,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 3236142820,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235377284,
      "name": "tcp_time_stamp_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 3235495916,
      "name": "tcp_time_stamp_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296292204,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296440160,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296778928,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297287972,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278811334,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278916854,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279130884,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279471342,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588667758,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588787953,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589025989,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589397313,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588379742,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588499889,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588751029,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589122305,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589103934,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589224129,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589462373,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589834177,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
  "name": "tcp_time_stamp_raw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589143694,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589264257,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589508709,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589885441,
      "name": "tcp_time_stamp_raw",
      "external": false,
      "loc": "include/net/tcp.h:772",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u32 tcp_time_stamp_raw()
```
</details>
</li>
</ul>
