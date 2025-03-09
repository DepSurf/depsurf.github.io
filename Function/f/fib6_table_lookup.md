# Function: <code>fib6_table_lookup</code>

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
struct fib6_info * fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588764080,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1819",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764080,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
struct fib6_info * fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588984320,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1810",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588984320,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589432848,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2152",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589432848,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589657200,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2158",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657200,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590670832,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2180",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590670832,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590731248,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2163",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590731248,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590656528,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2170",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590656528,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2173",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592738803,
      "name": "fib6_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071591470480,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2173",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594625388,
      "name": "fib6_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071593153184,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2173",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596359613,
      "name": "fib6_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071595050960,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2172",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596888196,
      "name": "fib6_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071595444336,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2174",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597812552,
      "name": "fib6_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071596286336,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503343552,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2158",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503343552,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236009288,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2158",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_nh_lookup_table",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236009288,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297106704,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2158",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297106704,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 924
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279352476,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2158",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_nh_lookup_table",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279352476,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589261568,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2158",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261568,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588986560,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2158",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588986560,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589698432,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2158",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589698432,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, struct fib6_result * res, int strict)
```

```json
{
  "name": "fib6_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589748160,
      "name": "fib6_table_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2158",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_lookup",
        "net/ipv6/fib6_rules.c:fib6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589748160,
      "name": "fib6_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
struct fib6_info * fib6_table_lookup(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, int strict)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fib6_result * res</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, table, oif, fl6, strict</code> ➡️ <code>net, table, oif, fl6, res, strict</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct fib6_info *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
