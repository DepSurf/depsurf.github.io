# Function: <code>ip6_setup_cork</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, int hlimit, int tclass, struct ipv6_txoptions * opt, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586993632,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1185",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_make_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586993632,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587440368,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1187",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440368,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 786
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587643760,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1214",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587643760,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 794
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587796816,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1212",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587796816,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588322608,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1168",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588322608,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588679840,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1159",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588679840,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895056,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1168",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895056,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1232",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589336688,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
    },
    {
      "addr": 18446744071589350784,
      "name": "ip6_setup_cork.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589560880,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1235",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589560880,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590568128,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1305",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590568128,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590628112,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1344",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590628112,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590551424,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1375",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590551424,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1354",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361360,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1235
    },
    {
      "addr": 18446744071592735534,
      "name": "ip6_setup_cork.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1375",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593032880,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
    },
    {
      "addr": 18446744071594622052,
      "name": "ip6_setup_cork.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1393",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594924624,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
    },
    {
      "addr": 18446744071596356708,
      "name": "ip6_setup_cork.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1394",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595316272,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1130
    },
    {
      "addr": 18446744071596885494,
      "name": "ip6_setup_cork.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1335",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596157712,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1111
    },
    {
      "addr": 18446744071597810100,
      "name": "ip6_setup_cork.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503232648,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1235",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503232648,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235905400,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1235",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235905400,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296981488,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1235",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296981488,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279266764,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1235",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279266764,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589165248,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1235",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589165248,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588890240,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1235",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890240,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589602112,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1235",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589602112,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
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
int ip6_setup_cork(struct sock * sk, struct inet_cork_full * cork, struct inet6_cork * v6_cork, struct ipcm6_cookie * ipc6, struct rt6_info * rt, struct flowi6 * fl6)
```

```json
{
  "name": "ip6_setup_cork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650384,
      "name": "ip6_setup_cork",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:1235",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650384,
      "name": "ip6_setup_cork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ipcm6_cookie * ipc6</code>
</li>
<li>
<b>Param removed. </b>
<code>int hlimit</code>
</li>
<li>
<b>Param removed. </b>
<code>int tclass</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ipv6_txoptions * opt</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, cork, v6_cork, hlimit, tclass, opt, rt, fl6</code> ➡️ <code>sk, cork, v6_cork, ipc6, rt, fl6</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct flowi6 * fl6</code>
</li>
</ul>
</details>
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
