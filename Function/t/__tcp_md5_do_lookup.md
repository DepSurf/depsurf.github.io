# Function: <code>__tcp_md5_do_lookup</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588535536,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:980",
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
      "addr": 18446744071588535536,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588946192,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:981",
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
      "addr": 18446744071588946192,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589170400,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:988",
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
      "addr": 18446744071589170400,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, int l3index, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590139680,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1013",
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
      "addr": 18446744071590139680,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, int l3index, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590187920,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1026",
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
      "addr": 18446744071590187920,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, int l3index, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590101888,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1041",
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
      "addr": 18446744071590101888,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, int l3index, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1055",
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
      "addr": 18446744071592719985,
      "name": "__tcp_md5_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071590876288,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, int l3index, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1063",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594606413,
      "name": "__tcp_md5_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071592514000,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, int l3index, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1074",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596341750,
      "name": "__tcp_md5_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071594369936,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, int l3index, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1081",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596871026,
      "name": "__tcp_md5_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071594760176,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, int l3index, const union tcp_ao_addr * addr, int family, bool any_l3index)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1240",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ao.c:tcp_ao_add_cmd",
        "net/ipv4/tcp_ao.c:tcp_ao_add_cmd",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597794666,
      "name": "__tcp_md5_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071595565680,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502785032,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:988",
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
      "addr": 18446603336502785032,
      "name": "__tcp_md5_do_lookup",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235484104,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:988",
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
      "addr": 3235484104,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296427328,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:988",
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
      "addr": 13835058055296427328,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278900392,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:988",
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
      "addr": 18446743936278900392,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588776784,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:988",
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
      "addr": 18446744071588776784,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588488720,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:988",
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
      "addr": 18446744071588488720,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212960,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:988",
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
      "addr": 18446744071589212960,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```

```json
{
  "name": "__tcp_md5_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589254208,
      "name": "__tcp_md5_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:988",
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
      "addr": 18446744071589254208,
      "name": "__tcp_md5_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct tcp_md5sig_key * __tcp_md5_do_lookup(const struct sock * sk, const union tcp_md5_addr * addr, int family)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int l3index</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, addr, family</code> ➡️ <code>sk, l3index, addr, family</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool any_l3index</code>
</li>
<li>
<b>Param type changed. </b>
<code>const union tcp_md5_addr * addr</code> ➡️ <code>const union tcp_ao_addr * addr</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
