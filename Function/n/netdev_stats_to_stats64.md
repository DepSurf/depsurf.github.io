# Function: <code>netdev_stats_to_stats64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586266560,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:6966",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats"
      ],
      "caller_func": [
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586266560,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586692000,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:7477",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586692000,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586878272,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:7647",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586878272,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587002592,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:7836",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002592,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587501248,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:8015",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587501248,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587806160,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:8278",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806160,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587941808,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:8908",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941808,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588250928,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9013",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588250928,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588456144,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9351",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456144,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589323776,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9807",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589323776,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589322736,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:10452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_tstats64",
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322736,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589218480,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:10624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_tstats64",
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218480,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589942896,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:10631",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_tstats64",
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942896,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591477216,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:10376",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_tstats64",
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591477216,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593246320,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:10363",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_tstats64",
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593246320,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593707040,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:10375",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_tstats64",
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593707040,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594485264,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:10568",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_tstats64",
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594485264,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501981344,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9351",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501981344,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234735148,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9351",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234735148,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295409712,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9351",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295409712,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278279614,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9351",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278279614,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588062928,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9351",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588062928,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587776016,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9351",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587776016,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394704,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9351",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394704,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 * stats64, const struct net_device_stats * netdev_stats)
```

```json
{
  "name": "netdev_stats_to_stats64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588530384,
      "name": "netdev_stats_to_stats64",
      "external": true,
      "loc": "net/core/dev.c:9351",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_stats",
        "net/core/dev.c:dev_get_stats",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588530384,
      "name": "netdev_stats_to_stats64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
