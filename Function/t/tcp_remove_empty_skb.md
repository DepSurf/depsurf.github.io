# Function: <code>tcp_remove_empty_skb</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588853976,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:944",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835424,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589077306,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:946",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589058544,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_remove_empty_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590023648,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:953",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590023648,
      "name": "tcp_remove_empty_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_remove_empty_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590069312,
      "name": "tcp_remove_empty_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:957",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069312,
      "name": "tcp_remove_empty_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_remove_empty_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589983680,
      "name": "tcp_remove_empty_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589983680,
      "name": "tcp_remove_empty_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_remove_empty_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590753136,
      "name": "tcp_remove_empty_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:953",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590753136,
      "name": "tcp_remove_empty_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void tcp_remove_empty_skb(struct sock * sk)
```

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592386768,
      "name": "tcp_remove_empty_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:927",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592386768,
      "name": "tcp_remove_empty_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void tcp_remove_empty_skb(struct sock * sk)
```

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594237216,
      "name": "tcp_remove_empty_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:928",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594237216,
      "name": "tcp_remove_empty_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void tcp_remove_empty_skb(struct sock * sk)
```

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594623376,
      "name": "tcp_remove_empty_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:931",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594623376,
      "name": "tcp_remove_empty_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void tcp_remove_empty_skb(struct sock * sk)
```

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595426384,
      "name": "tcp_remove_empty_skb",
      "external": true,
      "loc": "net/ipv4/tcp.c:937",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595426384,
      "name": "tcp_remove_empty_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502693440,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:946",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502670192,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235394860,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:946",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235374424,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296304172,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:946",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296278720,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278823372,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:946",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278808396,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588683690,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:946",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588664928,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588395674,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:946",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376912,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589119866,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:946",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589101104,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_remove_empty_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589159690,
      "name": "tcp_remove_empty_skb",
      "external": false,
      "loc": "net/ipv4/tcp.c:946",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140864,
      "name": "tcp_remove_empty_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void tcp_remove_empty_skb(struct sock * sk, struct sk_buff * skb)
```
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sk_buff * skb</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
