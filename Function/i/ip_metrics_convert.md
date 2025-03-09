# Function: <code>ip_metrics_convert</code>

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
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics)
```

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588530464,
      "name": "ip_metrics_convert",
      "external": true,
      "loc": "net/ipv4/metrics.c:8",
      "file": "net/ipv4/metrics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588530464,
      "name": "ip_metrics_convert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588726387,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:8",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589147539,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589371651,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590356496,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590356496,
      "name": "ip_metrics_convert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590411712,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590411712,
      "name": "ip_metrics_convert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590327760,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590327760,
      "name": "ip_metrics_convert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591115488,
      "name": "ip_metrics_convert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
    },
    {
      "addr": 18446744071592729618,
      "name": "ip_metrics_convert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592768288,
      "name": "ip_metrics_convert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071594616013,
      "name": "ip_metrics_convert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:10",
      "file": "net/ipv4/metrics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594641280,
      "name": "ip_metrics_convert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071596350858,
      "name": "ip_metrics_convert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:10",
      "file": "net/ipv4/metrics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595033712,
      "name": "ip_metrics_convert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071596879767,
      "name": "ip_metrics_convert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:10",
      "file": "net/ipv4/metrics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595846560,
      "name": "ip_metrics_convert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071597803846,
      "name": "ip_metrics_convert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503014012,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235703456,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296708116,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279086654,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588977827,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588689763,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589414211,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_metrics_convert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589457747,
      "name": "ip_metrics_convert",
      "external": false,
      "loc": "net/ipv4/metrics.c:9",
      "file": "net/ipv4/metrics.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ip_metrics_convert(struct net * net, struct nlattr * fc_mx, int fc_mx_len, u32 * metrics, struct netlink_ext_ack * extack)
```
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
