# Function: <code>sock_kfree_s</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586195488,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:1797",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/exthdrs.c:ipv6_renew_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195488,
      "name": "sock_kfree_s",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586617040,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:1826",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586617040,
      "name": "sock_kfree_s",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586793280,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:1824",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793280,
      "name": "sock_kfree_s",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586925024,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:1963",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925024,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587418000,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2001",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/exthdrs.c:ipv6_renew_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587418000,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587712144,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2021",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587712144,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845456,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2017",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845456,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588158416,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2158",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588158416,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588362064,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2173",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588362064,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589220128,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2282",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589220128,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589218288,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2274",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218288,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589107248,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2297",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589107248,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589830128,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2421",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589830128,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591353040,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2590",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_free_local_addr_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591353040,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593102928,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2669",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:__tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_free_local_addr_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593102928,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593559728,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2729",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/tcp_ipv4.c:__tcp_md5_do_add",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_free_local_addr_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593559728,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594326592,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2709",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit",
        "net/mptcp/pm_userspace.c:mptcp_free_local_addr_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594326592,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501868216,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2173",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501868216,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234635524,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2173",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234635524,
      "name": "sock_kfree_s",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295276496,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2173",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295276496,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278187080,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2173",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278187080,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587968848,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2173",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587968848,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587681952,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2173",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587681952,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588300624,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2173",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588300624,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sock_kfree_s(struct sock * sk, void * mem, int size)
```

```json
{
  "name": "sock_kfree_s",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588435952,
      "name": "sock_kfree_s",
      "external": true,
      "loc": "net/core/sock.c:2173",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588435952,
      "name": "sock_kfree_s",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
