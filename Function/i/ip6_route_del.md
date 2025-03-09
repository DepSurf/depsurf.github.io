# Function: <code>ip6_route_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config * cfg)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052704,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:2054",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052704,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config * cfg)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587501728,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:2125",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587501728,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config * cfg)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587706112,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:2146",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587706112,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867280,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:2214",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867280,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588395664,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:2911",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588395664,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 873
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588758144,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3266",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758144,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588977536,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977536,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 973
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589430304,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3849",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589430304,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589654656,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3862",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589654656,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590668736,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3915",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590668736,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590728960,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3899",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590728960,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590654240,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590654240,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591468096,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:4043",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591468096,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593148608,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:4019",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593148608,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 929
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595046176,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:4019",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595046176,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 929
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595439632,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:4017",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595439632,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596281632,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:4019",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596281632,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503330968,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3862",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503330968,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236006704,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3862",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236006704,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297103344,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3862",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297103344,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1412
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279347092,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3862",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279347092,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589259024,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3862",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589259024,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588984016,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3862",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588984016,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589695888,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3862",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589695888,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
int ip6_route_del(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589745552,
      "name": "ip6_route_del",
      "external": false,
      "loc": "net/ipv6/route.c:3862",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589745552,
      "name": "ip6_route_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
