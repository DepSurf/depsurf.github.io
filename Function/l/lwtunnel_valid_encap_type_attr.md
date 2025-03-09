# Function: <code>lwtunnel_valid_encap_type_attr</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075696,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:160",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075696,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587203840,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:180",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587203840,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718112,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:182",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718112,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588051744,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:182",
      "file": "net/core/lwtunnel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588051744,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588220032,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:182",
      "file": "net/core/lwtunnel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588220032,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588553616,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588553616,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770496,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770496,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642416,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:179",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642416,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589666016,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:179",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589666016,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589557728,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:179",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589557728,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590302416,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:184",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590302416,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591886656,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:184",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591886656,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593688720,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:187",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593688720,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594169504,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:187",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594169504,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594966048,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:187",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594966048,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502336536,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502336536,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235076272,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235076272,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295857040,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295857040,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278558638,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278558638,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376880,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376880,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588089568,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089568,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588709056,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709056,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588849024,
      "name": "lwtunnel_valid_encap_type_attr",
      "external": true,
      "loc": "net/core/lwtunnel.c:177",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588849024,
      "name": "lwtunnel_valid_encap_type_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr * attr, int remaining)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
