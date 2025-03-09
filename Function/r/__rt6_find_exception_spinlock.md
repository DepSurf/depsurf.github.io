# Function: <code>__rt6_find_exception_spinlock</code>

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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588397008,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1207",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588397008,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588755376,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1329",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588755376,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588975616,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975616,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589421904,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1493",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589421904,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589646224,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646224,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590654560,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1521",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590654560,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590713680,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1504",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590713680,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590631600,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1514",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590631600,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591444752,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1514",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591444752,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593124800,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1514",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593124800,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595020928,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1514",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595020928,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595414432,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1513",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595414432,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596256240,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1515",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596256240,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503328632,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503328632,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236002068,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236002068,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297096768,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297096768,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279346356,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279346356,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589250592,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589250592,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588975584,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975584,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589687456,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687456,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "__rt6_find_exception_spinlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589736784,
      "name": "__rt6_find_exception_spinlock",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589736784,
      "name": "__rt6_find_exception_spinlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct rt6_exception * __rt6_find_exception_spinlock(struct rt6_exception_bucket * * bucket, const struct in6_addr * daddr, const struct in6_addr * saddr)
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
