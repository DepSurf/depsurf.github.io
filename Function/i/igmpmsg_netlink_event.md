# Function: <code>igmpmsg_netlink_event</code>

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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587665451,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2361",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588191352,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2526",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588545357,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2409",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588741578,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2422",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589173885,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2434",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589398741,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2435",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
void igmpmsg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590387536,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2403",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590387536,
      "name": "igmpmsg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
void igmpmsg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590445760,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2411",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590445760,
      "name": "igmpmsg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
void igmpmsg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590371024,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2411",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590371024,
      "name": "igmpmsg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
void igmpmsg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591162208,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2413",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591162208,
      "name": "igmpmsg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
void igmpmsg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592820432,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2407",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592820432,
      "name": "igmpmsg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
void igmpmsg_netlink_event(const struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594696864,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2414",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594696864,
      "name": "igmpmsg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
void igmpmsg_netlink_event(const struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595088784,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2429",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595088784,
      "name": "igmpmsg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
void igmpmsg_netlink_event(const struct mr_table * mrt, struct sk_buff * pkt)
```

```json
{
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595901904,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2427",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595901904,
      "name": "igmpmsg_netlink_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503047448,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2435",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235731984,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2435",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296745896,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2435",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279111726,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2435",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589004005,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2435",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588727061,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2435",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589440389,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2435",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
  "name": "igmpmsg_netlink_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589485034,
      "name": "igmpmsg_netlink_event",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2435",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
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
void igmpmsg_netlink_event(struct mr_table * mrt, struct sk_buff * pkt)
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
