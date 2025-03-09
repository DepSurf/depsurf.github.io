# Function: <code>mr_table_alloc</code>

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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563200,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:31",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563200,
      "name": "mr_table_alloc",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588760480,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588760480,
      "name": "mr_table_alloc",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589193424,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589193424,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589418864,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418864,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590405264,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590405264,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590463104,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590463104,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590388864,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590388864,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591183344,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591183344,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592841888,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592841888,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594719392,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594719392,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595111408,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595111408,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595924080,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595924080,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503068880,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503068880,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235753024,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235753024,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296775056,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296775056,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279128458,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279128458,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589023232,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589023232,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588746288,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588746288,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589459616,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459616,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```

```json
{
  "name": "mr_table_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589505952,
      "name": "mr_table_alloc",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:32",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505952,
      "name": "mr_table_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct mr_table * mr_table_alloc(struct net * net, u32 id, struct mr_table_ops * ops, void (*)(struct timer_list *) expire_func, void (*)(struct mr_table *, struct net *) table_set)
```
</details>
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
