# Function: <code>rt6_insert_exception</code>

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
int rt6_insert_exception(struct rt6_info * nrt, struct rt6_info * ort)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588397200,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1269",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588397200,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int rt6_insert_exception(struct rt6_info * nrt, struct fib6_info * ort)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588756016,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1412",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588756016,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
int rt6_insert_exception(struct rt6_info * nrt, struct fib6_info * ort)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588976208,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1426",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588976208,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589424128,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1630",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589424128,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589648448,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1636",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589648448,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590656896,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1658",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590656896,
      "name": "rt6_insert_exception.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590716000,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1641",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590716000,
      "name": "rt6_insert_exception.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590640656,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1651",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590640656,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591452192,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1651",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591452192,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593133280,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1651",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593133280,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595030352,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1651",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595030352,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595423792,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1650",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595423792,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596265616,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1652",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596265616,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503337144,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1636",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503337144,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236003312,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1636",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236003312,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297098352,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1636",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297098352,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279348618,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1636",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279348618,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589252816,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1636",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252816,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588977808,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1636",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977808,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589689680,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1636",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689680,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```

```json
{
  "name": "rt6_insert_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589739056,
      "name": "rt6_insert_exception",
      "external": false,
      "loc": "net/ipv6/route.c:1636",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589739056,
      "name": "rt6_insert_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
int rt6_insert_exception(struct rt6_info * nrt, struct rt6_info * ort)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt6_info * ort</code> ➡️ <code>struct fib6_info * ort</code>
</li>
</ul>
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
<code>const struct fib6_result * res</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_info * ort</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int rt6_insert_exception(struct rt6_info * nrt, const struct fib6_result * res)
```
</details>
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
