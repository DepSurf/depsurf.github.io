# Function: <code>tcp_make_synack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, bool attach_req)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663088,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2942",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663088,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587109424,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2986",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587109424,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 997
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587307312,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3110",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307312,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1005
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587439232,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3135",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587439232,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1041
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587959728,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3194",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587959728,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1075
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588310000,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3175",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588310000,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1098
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588498880,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588498880,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1063
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588908384,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3234",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588908384,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589132416,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3266",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132416,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590101424,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3339",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590101424,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 890
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type, struct sk_buff * syn_skb)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590148640,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3512",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590148640,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type, struct sk_buff * syn_skb)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590062720,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3509",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590062720,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type, struct sk_buff * syn_skb)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590836560,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3510",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590836560,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type, struct sk_buff * syn_skb)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592472464,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3516",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592472464,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1132
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type, struct sk_buff * syn_skb)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594328048,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3518",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594328048,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1132
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type, struct sk_buff * syn_skb)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594713856,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3600",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594713856,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1104
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type, struct sk_buff * syn_skb)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3664",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597793371,
      "name": "tcp_make_synack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071595519728,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1361
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502749864,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3266",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502749864,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1048
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235452032,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3266",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235452032,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1100
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296374928,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3266",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296374928,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1456
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278872772,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3266",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278872772,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1070
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588738800,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3266",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588738800,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588450752,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3266",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450752,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589174976,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3266",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589174976,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
struct sk_buff * tcp_make_synack(const struct sock * sk, struct dst_entry * dst, struct request_sock * req, struct tcp_fastopen_cookie * foc, enum tcp_synack_type synack_type)
```

```json
{
  "name": "tcp_make_synack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589215024,
      "name": "tcp_make_synack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3266",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589215024,
      "name": "tcp_make_synack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1122
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum tcp_synack_type synack_type</code>
</li>
<li>
<b>Param removed. </b>
<code>bool attach_req</code>
</li>
</ul>
</details>
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff * syn_skb</code>
</li>
</ul>
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
