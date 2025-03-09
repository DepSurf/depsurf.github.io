# Function: <code>mr_dump</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588562784,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:330",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588562784,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588760064,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:388",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588760064,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589193008,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589193008,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589418448,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418448,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *, struct netlink_ext_ack *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock, struct netlink_ext_ack * extack)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590404224,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590404224,
      "name": "mr_dump.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071590404592,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *, struct netlink_ext_ack *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock, struct netlink_ext_ack * extack)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590462064,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590462064,
      "name": "mr_dump.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071590462432,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *, struct netlink_ext_ack *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock, struct netlink_ext_ack * extack)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590387872,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590387872,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *, struct netlink_ext_ack *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock, struct netlink_ext_ack * extack)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591182144,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591182144,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *, struct netlink_ext_ack *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock, struct netlink_ext_ack * extack)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592842144,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592842144,
      "name": "mr_dump",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *, struct netlink_ext_ack *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, struct netlink_ext_ack * extack)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594717936,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:396",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594717936,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *, struct netlink_ext_ack *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, struct netlink_ext_ack * extack)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595109936,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:396",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595109936,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *, struct netlink_ext_ack *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, struct netlink_ext_ack * extack)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595922608,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:396",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595922608,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503069728,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503069728,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235754304,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235754304,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296774448,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296774448,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279128130,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279128130,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589022816,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589022816,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588745872,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588745872,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589459200,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459200,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
```

```json
{
  "name": "mr_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589505536,
      "name": "mr_dump",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:387",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_dump",
        "net/ipv6/ip6mr.c:ip6mr_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505536,
      "name": "mr_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int mr_dump(struct net * net, struct notifier_block * nb, short unsigned int family, int (*)(struct net *, struct notifier_block *) rules_dump, struct mr_table * (*)(struct net *, struct mr_table *) mr_iter, rwlock_t * mrt_lock)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*)(struct net *, struct notifier_block *) rules_dump</code> ➡️ <code>int (*)(struct net *, struct notifier_block *, struct netlink_ext_ack *) rules_dump</code>
</li>
</ul>
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
<b>Param removed. </b>
<code>rwlock_t * mrt_lock</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, nb, family, rules_dump, mr_iter, mrt_lock, extack</code> ➡️ <code>net, nb, family, rules_dump, mr_iter, extack</code>
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
