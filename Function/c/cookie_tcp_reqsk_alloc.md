# Function: <code>cookie_tcp_reqsk_alloc</code>

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
struct request_sock * cookie_tcp_reqsk_alloc(const struct request_sock_ops * ops, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "cookie_tcp_reqsk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590466848,
      "name": "cookie_tcp_reqsk_alloc",
      "external": true,
      "loc": "net/ipv4/syncookies.c:285",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590466848,
      "name": "cookie_tcp_reqsk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct request_sock * cookie_tcp_reqsk_alloc(const struct request_sock_ops * ops, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "cookie_tcp_reqsk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590392624,
      "name": "cookie_tcp_reqsk_alloc",
      "external": true,
      "loc": "net/ipv4/syncookies.c:285",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590392624,
      "name": "cookie_tcp_reqsk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct request_sock * cookie_tcp_reqsk_alloc(const struct request_sock_ops * ops, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "cookie_tcp_reqsk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cookie_tcp_reqsk_alloc",
      "external": true,
      "loc": "net/ipv4/syncookies.c:285",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592733737,
      "name": "cookie_tcp_reqsk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071591187856,
      "name": "cookie_tcp_reqsk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
struct request_sock * cookie_tcp_reqsk_alloc(const struct request_sock_ops * ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "cookie_tcp_reqsk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cookie_tcp_reqsk_alloc",
      "external": true,
      "loc": "net/ipv4/syncookies.c:283",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594620276,
      "name": "cookie_tcp_reqsk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071592847200,
      "name": "cookie_tcp_reqsk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
struct request_sock * cookie_tcp_reqsk_alloc(const struct request_sock_ops * ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "cookie_tcp_reqsk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cookie_tcp_reqsk_alloc",
      "external": true,
      "loc": "net/ipv4/syncookies.c:283",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596355065,
      "name": "cookie_tcp_reqsk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071594724256,
      "name": "cookie_tcp_reqsk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct request_sock * cookie_tcp_reqsk_alloc(const struct request_sock_ops * ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "cookie_tcp_reqsk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cookie_tcp_reqsk_alloc",
      "external": true,
      "loc": "net/ipv4/syncookies.c:283",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596883873,
      "name": "cookie_tcp_reqsk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071595116336,
      "name": "cookie_tcp_reqsk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct request_sock * cookie_tcp_reqsk_alloc(const struct request_sock_ops * ops, struct sock * sk, struct sk_buff * skb, struct tcp_options_received * tcp_opt, int mss, u32 tsoff)
```

```json
{
  "name": "cookie_tcp_reqsk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cookie_tcp_reqsk_alloc",
      "external": true,
      "loc": "net/ipv4/syncookies.c:307",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597808003,
      "name": "cookie_tcp_reqsk_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071595928304,
      "name": "cookie_tcp_reqsk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
struct request_sock * cookie_tcp_reqsk_alloc(const struct request_sock_ops * ops, struct sock * sk, struct sk_buff * skb)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct tcp_request_sock_ops * af_ops</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, sk, skb</code> ➡️ <code>ops, af_ops, sk, skb</code>
</li>
</ul>
</details>
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
<code>struct tcp_options_received * tcp_opt</code>
</li>
<li>
<b>Param added. </b>
<code>int mss</code>
</li>
<li>
<b>Param added. </b>
<code>u32 tsoff</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct tcp_request_sock_ops * af_ops</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, af_ops, sk, skb</code> ➡️ <code>ops, sk, skb, tcp_opt, mss, tsoff</code>
</li>
</ul>
</details>
</li>
</ul>
