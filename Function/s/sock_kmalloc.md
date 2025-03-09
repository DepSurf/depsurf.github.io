# Function: <code>sock_kmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586187808,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:1763",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/exthdrs.c:ipv6_dup_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187808,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586608096,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:1792",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586608096,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586792448,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:1790",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792448,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586916336,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:1929",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586916336,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587408384,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:1967",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408384,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587715280,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:1987",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715280,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587848720,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:1983",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587848720,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588160352,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2124",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588160352,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588365584,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2139",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588365584,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589218080,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2248",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218080,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589216144,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2240",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589216144,
      "name": "sock_kmalloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071589216208,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589109792,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2263",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589109792,
      "name": "sock_kmalloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071589109856,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589827936,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2387",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589827936,
      "name": "sock_kmalloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071589828000,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591346752,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2554",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346752,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593102464,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2633",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:__tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593102464,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593553952,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2693",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:__tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593553952,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594326144,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2673",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:__tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv4/tcp_ao.c:tcp_ao_add_cmd",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options",
        "net/mptcp/protocol.c:mptcp_copy_ip_options",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594326144,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501871152,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2139",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501871152,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234639436,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2139",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234639436,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295281504,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2139",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295281504,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278191080,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2139",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278191080,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587972368,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2139",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972368,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587685472,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2139",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685472,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588304144,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2139",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588304144,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void * sock_kmalloc(struct sock * sk, int size, gfp_t priority)
```

```json
{
  "name": "sock_kmalloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588439328,
      "name": "sock_kmalloc",
      "external": true,
      "loc": "net/core/sock.c:2139",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_renew_options",
        "net/ipv6/exthdrs.c:ipv6_dup_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439328,
      "name": "sock_kmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
