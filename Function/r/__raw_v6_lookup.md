# Function: <code>__raw_v6_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123312,
      "name": "__raw_v6_lookup",
      "external": false,
      "loc": "net/ipv6/raw.c:72",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123312,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587574608,
      "name": "__raw_v6_lookup",
      "external": false,
      "loc": "net/ipv6/raw.c:72",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574608,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587778624,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:73",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587778624,
      "name": "__raw_v6_lookup",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587935280,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:73",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587935280,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588470720,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:73",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588470720,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588834384,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:73",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588834384,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589057872,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:73",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589057872,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589511152,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589511152,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589735248,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589735248,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590753296,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590753296,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590812720,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590812720,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590739744,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590739744,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591556304,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591556304,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503426440,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503426440,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236087772,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236087772,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297207728,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297207728,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279418354,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279418354,
      "name": "__raw_v6_lookup",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589339616,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589339616,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589064608,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589064608,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589776480,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589776480,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__raw_v6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589827232,
      "name": "__raw_v6_lookup",
      "external": true,
      "loc": "net/ipv6/raw.c:69",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589827232,
      "name": "__raw_v6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sdif</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct sock * __raw_v6_lookup(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```
</details>
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
