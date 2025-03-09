# Function: <code>mrt6msg_netlink_event</code>

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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588025755,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2479",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588563179,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2484",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588927013,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2385",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589151109,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2417",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589605411,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589829507,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mrt6msg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590855792,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2440",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590855792,
      "name": "mrt6msg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
void mrt6msg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590916576,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2441",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590916576,
      "name": "mrt6msg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
void mrt6msg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590846048,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2441",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590846048,
      "name": "mrt6msg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
void mrt6msg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591674640,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2442",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591674640,
      "name": "mrt6msg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
void mrt6msg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593371344,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2463",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593371344,
      "name": "mrt6msg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
void mrt6msg_netlink_event(const struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595279344,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2468",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595279344,
      "name": "mrt6msg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
void mrt6msg_netlink_event(const struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595674512,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2460",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595674512,
      "name": "mrt6msg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
void mrt6msg_netlink_event(const struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596522336,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2458",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596522336,
      "name": "mrt6msg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503541372,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236191288,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297337816,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279505402,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589433875,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589158867,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589870739,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
  "name": "mrt6msg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589922232,
      "name": "mrt6msg_netlink_event",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2435",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void mrt6msg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mr_table * mrt</code> ➡️ <code>const struct mr_table * mrt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
