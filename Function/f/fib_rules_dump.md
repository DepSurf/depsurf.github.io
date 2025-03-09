# Function: <code>fib_rules_dump</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587688128,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:331",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587688128,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588020160,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:356",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588020160,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588187920,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:356",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588187920,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588514096,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588514096,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588722672,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588722672,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589596128,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:355",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589596128,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589600864,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:378",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589600864,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589489456,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:378",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589489456,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590230240,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:378",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590230240,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591812672,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:378",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591812672,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593608768,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:378",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593608768,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594082128,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:378",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594082128,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594876768,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:377",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594876768,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502287896,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502287896,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235027768,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235027768,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295789376,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295789376,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278519498,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278519498,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588329408,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588329408,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588042112,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588042112,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588661232,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588661232,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```

```json
{
  "name": "fib_rules_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588801072,
      "name": "fib_rules_dump",
      "external": true,
      "loc": "net/core/fib_rules.c:353",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rules_dump",
        "net/ipv4/ipmr.c:ipmr_rules_dump",
        "net/ipv6/ip6mr.c:ip6mr_rules_dump",
        "net/ipv6/fib6_rules.c:fib6_rules_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588801072,
      "name": "fib_rules_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int fib_rules_dump(struct net * net, struct notifier_block * nb, int family)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
