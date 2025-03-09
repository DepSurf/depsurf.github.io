# Function: <code>tcp_reqsk_record_syn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586636034,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6139",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587087643,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6192",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587284461,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6284",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587415338,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6282",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587935229,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6179",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588284477,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6343",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588474115,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6394",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588863664,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6452",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863664,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589087872,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6506",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589087872,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590051648,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6565",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590051648,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590096768,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6701",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590096768,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590010688,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6710",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590010688,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590781728,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6745",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590781728,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592416688,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592416688,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594270128,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6861",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594270128,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594656208,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6868",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594656208,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595460272,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:7028",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595460272,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502716948,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6506",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235414564,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6506",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296317680,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6506",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296317680,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278848932,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6506",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588694256,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6506",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588694256,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588406240,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6506",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406240,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130432,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6506",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130432,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```

```json
{
  "name": "tcp_reqsk_record_syn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589170256,
      "name": "tcp_reqsk_record_syn",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6506",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589170256,
      "name": "tcp_reqsk_record_syn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void tcp_reqsk_record_syn(const struct sock * sk, struct request_sock * req, const struct sk_buff * skb)
```
</details>
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
