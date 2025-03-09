# Function: <code>fib6_clean_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct rt6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587086240,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1695",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_remove_prefsrc",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:rt6_mtu_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587086240,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct rt6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587536844,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1697",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587536736,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct rt6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587741276,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1703",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587741168,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct rt6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587895292,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1745",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587895184,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void fib6_clean_all(struct net * net, int (*)(struct rt6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588430188,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1988",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588430080,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588791655,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2043",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588791520,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589012094,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2079",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011920,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589463834,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2154",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589463664,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589688186,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2155",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688016,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590704346,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2258",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590704176,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590764890,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2262",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590764720,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590691802,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2263",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590691632,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591507690,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2264",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591507520,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593192758,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2265",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593192544,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595092134,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2264",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595091888,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595485869,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2264",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595485632,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596328493,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2260",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596328256,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503377900,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2155",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503377584,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236041780,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2155",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236041556,
      "name": "fib6_clean_all",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297149308,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2155",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297149104,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279379562,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2155",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279379370,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589292554,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2155",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589292384,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589017546,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2155",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589017376,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589729418,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2155",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589729248,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fib6_clean_all(struct net * net, int (*)(struct fib6_info *, void *) func, void * arg)
```

```json
{
  "name": "fib6_clean_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589779786,
      "name": "fib6_clean_all",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:2155",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change",
        "net/ipv6/route.c:rt6_sync_down_dev",
        "net/ipv6/route.c:rt6_sync_up",
        "net/ipv6/route.c:rt6_clean_tohost",
        "net/ipv6/route.c:rt6_remove_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589779616,
      "name": "fib6_clean_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(struct rt6_info *, void *) func</code> ➡️ <code>int (*)(struct fib6_info *, void *) func</code>
</li>
</ul>
</details>
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
