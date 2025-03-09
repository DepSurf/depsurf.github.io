# Function: <code>rtm_dump_nexthop_bucket_cb</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtm_dump_nexthop_bucket_cb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590349822,
      "name": "rtm_dump_nexthop_bucket_cb",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3362",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_dump_nexthop_bucket",
        "net/ipv4/nexthop.c:rtm_dump_nexthop_bucket"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int rtm_dump_nexthop_bucket_cb(struct sk_buff * skb, struct netlink_callback * cb, struct nexthop * nh, void * data)
```

```json
{
  "name": "rtm_dump_nexthop_bucket_cb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591129658,
      "name": "rtm_dump_nexthop_bucket_cb",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_dump_nexthop_bucket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591129616,
      "name": "rtm_dump_nexthop_bucket_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071592731128,
      "name": "rtm_dump_nexthop_bucket_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int rtm_dump_nexthop_bucket_cb(struct sk_buff * skb, struct netlink_callback * cb, struct nexthop * nh, void * data)
```

```json
{
  "name": "rtm_dump_nexthop_bucket_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtm_dump_nexthop_bucket_cb",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3391",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_dump_nexthop_bucket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592783600,
      "name": "rtm_dump_nexthop_bucket_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071594617558,
      "name": "rtm_dump_nexthop_bucket_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int rtm_dump_nexthop_bucket_cb(struct sk_buff * skb, struct netlink_callback * cb, struct nexthop * nh, void * data)
```

```json
{
  "name": "rtm_dump_nexthop_bucket_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtm_dump_nexthop_bucket_cb",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3391",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_dump_nexthop_bucket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594657264,
      "name": "rtm_dump_nexthop_bucket_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071596352395,
      "name": "rtm_dump_nexthop_bucket_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int rtm_dump_nexthop_bucket_cb(struct sk_buff * skb, struct netlink_callback * cb, struct nexthop * nh, void * data)
```

```json
{
  "name": "rtm_dump_nexthop_bucket_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtm_dump_nexthop_bucket_cb",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3381",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_dump_nexthop_bucket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595049664,
      "name": "rtm_dump_nexthop_bucket_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071596881211,
      "name": "rtm_dump_nexthop_bucket_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int rtm_dump_nexthop_bucket_cb(struct sk_buff * skb, struct netlink_callback * cb, struct nexthop * nh, void * data)
```

```json
{
  "name": "rtm_dump_nexthop_bucket_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtm_dump_nexthop_bucket_cb",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3398",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_dump_nexthop_bucket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595862624,
      "name": "rtm_dump_nexthop_bucket_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071597805383,
      "name": "rtm_dump_nexthop_bucket_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int rtm_dump_nexthop_bucket_cb(struct sk_buff * skb, struct netlink_callback * cb, struct nexthop * nh, void * data)
```
</details>
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
