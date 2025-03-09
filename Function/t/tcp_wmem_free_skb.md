# Function: <code>tcp_wmem_free_skb</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592404607,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:293",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_remove_empty_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592421565,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:293",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592497248,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:293",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void tcp_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594252590,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:295",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_remove_empty_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594273565,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:295",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594352818,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:295",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594327424,
      "name": "tcp_wmem_free_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void tcp_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594639199,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:294",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_remove_empty_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594659645,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:294",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594740738,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:294",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594713232,
      "name": "tcp_wmem_free_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void tcp_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595442527,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:305",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_remove_empty_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595463805,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:305",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595546274,
      "name": "tcp_wmem_free_skb",
      "external": false,
      "loc": "include/net/tcp.h:305",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595515216,
      "name": "tcp_wmem_free_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void tcp_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
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
