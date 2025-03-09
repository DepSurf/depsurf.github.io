# Function: <code>mr_rtm_dumproute</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588561328,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:270",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588561328,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588758864,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:346",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758864,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191808,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191808,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589417248,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589417248,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590406880,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590406880,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590464720,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590464720,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590390480,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590390480,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592733669,
      "name": "mr_rtm_dumproute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071591185488,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594620198,
      "name": "mr_rtm_dumproute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071592844576,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:353",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596354987,
      "name": "mr_rtm_dumproute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071594721440,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:353",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596883795,
      "name": "mr_rtm_dumproute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071595113520,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:353",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597807967,
      "name": "mr_rtm_dumproute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071595926240,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503070928,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503070928,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235752660,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235752660,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296772336,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296772336,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279126990,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279126990,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589021616,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589021616,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744672,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744672,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458000,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458000,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_rtm_dumproute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589504368,
      "name": "mr_rtm_dumproute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:344",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589504368,
      "name": "mr_rtm_dumproute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int mr_rtm_dumproute(struct sk_buff * skb, struct netlink_callback * cb, struct mr_table * (*)(struct net *, struct mr_table *) iter, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fib_dump_filter * filter</code>
</li>
</ul>
</details>
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
