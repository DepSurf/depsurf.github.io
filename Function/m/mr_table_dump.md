# Function: <code>mr_table_dump</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588758272,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758272,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191216,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191216,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589416656,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589416656,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590406288,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590406288,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590464128,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590464128,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590389888,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590389888,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592733641,
      "name": "mr_table_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071591184464,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1023
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594620169,
      "name": "mr_table_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071592843424,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1152
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:298",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596354966,
      "name": "mr_table_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594720544,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:298",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596883774,
      "name": "mr_table_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595112624,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:298",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597807946,
      "name": "mr_table_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595925344,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503070208,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503070208,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235752044,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235752044,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296771488,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296771488,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279126502,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279126502,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589021024,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589021024,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744080,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744080,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589457408,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457408,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```

```json
{
  "name": "mr_table_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589503680,
      "name": "mr_table_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:289",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumproute",
        "net/ipv4/ipmr_base.c:mr_rtm_dumproute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_dumproute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589503680,
      "name": "mr_table_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int mr_table_dump(struct mr_table * mrt, struct sk_buff * skb, struct netlink_callback * cb, int (*)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int) fill, spinlock_t * lock, struct fib_dump_filter * filter)
```
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
