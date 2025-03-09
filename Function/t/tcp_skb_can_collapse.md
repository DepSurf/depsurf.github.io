# Function: <code>tcp_skb_can_collapse</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_skb_can_collapse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590074854,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:985",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590118319,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:985",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
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
  "name": "tcp_skb_can_collapse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590120774,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:990",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590166031,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:990",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
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
  "name": "tcp_skb_can_collapse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590034678,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:970",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590080590,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:970",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
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
  "name": "tcp_skb_can_collapse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590805814,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:963",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data",
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590855230,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:963",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool tcp_skb_can_collapse(const struct sk_buff * to, const struct sk_buff * from)
```

```json
{
  "name": "tcp_skb_can_collapse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592440493,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:978",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    },
    {
      "addr": 18446744071592490771,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:978",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592422000,
      "name": "tcp_skb_can_collapse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool tcp_skb_can_collapse(const struct sk_buff * to, const struct sk_buff * from)
```

```json
{
  "name": "tcp_skb_can_collapse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594294589,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    },
    {
      "addr": 18446744071594346067,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:991",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594274912,
      "name": "tcp_skb_can_collapse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
bool tcp_skb_can_collapse(const struct sk_buff * to, const struct sk_buff * from)
```

```json
{
  "name": "tcp_skb_can_collapse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594680768,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:986",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    },
    {
      "addr": 18446744071594733939,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:986",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594660992,
      "name": "tcp_skb_can_collapse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
bool tcp_skb_can_collapse(const struct sk_buff * to, const struct sk_buff * from)
```

```json
{
  "name": "tcp_skb_can_collapse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595485584,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:1023",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    },
    {
      "addr": 18446744071595539299,
      "name": "tcp_skb_can_collapse",
      "external": false,
      "loc": "include/net/tcp.h:1023",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595465440,
      "name": "tcp_skb_can_collapse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool tcp_skb_can_collapse(const struct sk_buff * to, const struct sk_buff * from)
```
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
