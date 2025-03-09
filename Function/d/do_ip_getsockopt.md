# Function: <code>do_ip_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586577584,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1266",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577584,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1852
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587020624,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1281",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587020624,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1946
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587216448,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1321",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587216448,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1966
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587348464,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1310",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587348464,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1946
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587868480,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1306",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587868480,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1958
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1310",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213888,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1926
    },
    {
      "addr": 18446744071588222791,
      "name": "do_ip_getsockopt.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1307",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588400224,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2194
    },
    {
      "addr": 18446744071588410023,
      "name": "do_ip_getsockopt.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588802496,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2198
    },
    {
      "addr": 18446744071588813807,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589025024,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2198
    },
    {
      "addr": 18446744071589037103,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1472",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589984944,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2315
    },
    {
      "addr": 18446744071589997909,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1515",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590028208,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2401
    },
    {
      "addr": 18446744071591634307,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1515",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589943648,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2510
    },
    {
      "addr": 18446744071591577710,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1515",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590710720,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2519
    },
    {
      "addr": 18446744071592714663,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1526",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592336688,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2320
    },
    {
      "addr": 18446744071594600741,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, sockptr_t optval, sockptr_t optlen)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594186288,
      "name": "do_ip_getsockopt",
      "external": true,
      "loc": "net/ipv4/ip_sockglue.c:1530",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sol_ip_sockopt",
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594186288,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2861
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, sockptr_t optval, sockptr_t optlen)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594573360,
      "name": "do_ip_getsockopt",
      "external": true,
      "loc": "net/ipv4/ip_sockglue.c:1552",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sol_ip_sockopt",
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594573360,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2883
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, sockptr_t optval, sockptr_t optlen)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595376544,
      "name": "do_ip_getsockopt",
      "external": true,
      "loc": "net/ipv4/ip_sockglue.c:1503",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sol_ip_sockopt",
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595376544,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3188
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502633424,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502633424,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235339364,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235339364,
      "name": "do_ip_getsockopt.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2548
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
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296231680,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296231680,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2980
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278779568,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278779568,
      "name": "do_ip_getsockopt.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1546
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631408,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2198
    },
    {
      "addr": 18446744071588643487,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343392,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2198
    },
    {
      "addr": 18446744071588355471,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589067584,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2198
    },
    {
      "addr": 18446744071589079663,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```

```json
{
  "name": "do_ip_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_ip_getsockopt",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1309",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589106960,
      "name": "do_ip_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2212
    },
    {
      "addr": 18446744071589119087,
      "name": "do_ip_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * optval</code> ➡️ <code>sockptr_t optval</code>
</li>
<li>
<b>Param type changed. </b>
<code>int * optlen</code> ➡️ <code>sockptr_t optlen</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_ip_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, unsigned int flags)
```
</details>
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
