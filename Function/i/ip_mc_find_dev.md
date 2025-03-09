# Function: <code>ip_mc_find_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586797168,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1696",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_msfget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797168,
      "name": "ip_mc_find_dev",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587246176,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1709",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246176,
      "name": "ip_mc_find_dev",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587446784,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1747",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446784,
      "name": "ip_mc_find_dev",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587583424,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1756",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587583424,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588107360,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1782",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588107360,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588462016,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1793",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462016,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588655696,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1809",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588655696,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589068608,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589068608,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589292768,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589292768,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590269120,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1809",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590269120,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590322064,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1809",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590322064,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590238080,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1817",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590238080,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591021552,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1817",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591021552,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592668288,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1824",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592668288,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594536144,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1824",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594536144,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594927936,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1825",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594927936,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595740144,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1827",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595740144,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502924784,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502924784,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235620064,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235620064,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296596880,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296596880,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279018080,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279018080,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588898944,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588898944,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588610880,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588610880,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589335328,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589335328,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct in_device * ip_mc_find_dev(struct net * net, struct ip_mreqn * imr)
```

```json
{
  "name": "ip_mc_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589377552,
      "name": "ip_mc_find_dev",
      "external": false,
      "loc": "net/ipv4/igmp.c:1811",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:__ip_mc_join_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589377552,
      "name": "ip_mc_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
