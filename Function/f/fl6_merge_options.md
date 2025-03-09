# Function: <code>fl6_merge_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587191792,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:294",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587191792,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587646672,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:294",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646672,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587853232,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:294",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853232,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588009920,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:294",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588009920,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588548448,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:294",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548448,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588912656,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:294",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588912656,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589136864,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:294",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589136864,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589590096,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589590096,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589814464,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589814464,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590837456,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590837456,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590897664,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590897664,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590827024,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590827024,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591646000,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591646000,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593340144,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593340144,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595246016,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595246016,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595641472,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:315",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595641472,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596488784,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:315",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596488784,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503519512,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503519512,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236175168,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236175168,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297317008,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297317008,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279490598,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279490598,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589418832,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418832,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589143824,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589143824,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589855696,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589855696,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct ipv6_txoptions * fl6_merge_options(struct ipv6_txoptions * opt_space, struct ip6_flowlabel * fl, struct ipv6_txoptions * fopt)
```

```json
{
  "name": "fl6_merge_options",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589907328,
      "name": "fl6_merge_options",
      "external": true,
      "loc": "net/ipv6/ip6_flowlabel.c:312",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589907328,
      "name": "fl6_merge_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
