# Function: <code>in4_pton</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586381600,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:120",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586381600,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586817648,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:120",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817648,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587005456,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:120",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005456,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587130736,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:122",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130736,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587634352,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:122",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587634352,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587944800,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:122",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587944800,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588092864,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:122",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092864,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588408912,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408912,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588614288,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588614288,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589469952,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469952,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589470848,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589470848,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589369280,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589369280,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590099616,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590099616,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591650320,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591650320,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593433856,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593433856,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593898768,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593898768,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594682064,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594682064,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502160752,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502160752,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234903392,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234903392,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295630224,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295630224,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278415244,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278415244,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588221024,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221024,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587933856,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933856,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588552848,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552848,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int in4_pton(const char * src, int srclen, u8 * dst, int delim, const char * * end)
```

```json
{
  "name": "in4_pton",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588690320,
      "name": "in4_pton",
      "external": true,
      "loc": "net/core/utils.c:118",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "net/core/utils.c:inet4_pton",
        "net/core/utils.c:in6_pton",
        "net/core/netpoll.c:netpoll_parse_ip_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588690320,
      "name": "in4_pton",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
