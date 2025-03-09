# Function: <code>xfrm_lookup_with_ifid</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3018",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588821876,
      "name": "xfrm_lookup_with_ifid.cold.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588815328,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2412
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3017",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255309,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071589248720,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2310
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3019",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589480320,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589474000,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2324
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3009",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590470851,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071590466016,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1166
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3030",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591635636,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071590524384,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1197
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3029",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591579054,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071590449632,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1190
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3029",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592734203,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071591251104,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3032",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594620734,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071592915920,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1452
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594796768,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3106",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594796768,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1464
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595188384,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3108",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595188384,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1450
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596029072,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3130",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596029072,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1450
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503132008,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3019",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503132008,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2364
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235812236,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3019",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235812236,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2324
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296852320,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3019",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296852320,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2856
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279178866,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3019",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279178866,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1962
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3019",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589084688,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589078368,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2324
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3019",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588809728,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588803408,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2324
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3019",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589521552,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589515232,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2324
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
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```

```json
{
  "name": "xfrm_lookup_with_ifid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup_with_ifid",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3019",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589568649,
      "name": "xfrm_lookup_with_ifid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589562144,
      "name": "xfrm_lookup_with_ifid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2451
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct dst_entry * xfrm_lookup_with_ifid(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags, u32 if_id)
```
</details>
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
