# Function: <code>net_ns_get_ownership</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587785632,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:461",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785632,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587918480,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:461",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918480,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588227536,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:499",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227536,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588432176,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:501",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432176,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589297984,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:507",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589297984,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589296544,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:508",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589296544,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589190432,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:499",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190432,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589911968,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:499",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589911968,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591442896,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:498",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591442896,
      "name": "net_ns_get_ownership",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593209952,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:517",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593209952,
      "name": "net_ns_get_ownership",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593670192,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:518",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593670192,
      "name": "net_ns_get_ownership",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594448272,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:522",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594448272,
      "name": "net_ns_get_ownership",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501953464,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:501",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501953464,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234709088,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:501",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234709088,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295376256,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:501",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295376256,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278257406,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:501",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278257406,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588038960,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:501",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588038960,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587752048,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:501",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587752048,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370736,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:501",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588370736,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "net_ns_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588506400,
      "name": "net_ns_get_ownership",
      "external": true,
      "loc": "net/core/net_namespace.c:501",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:net_get_ownership",
        "net/core/net-sysfs.c:netdev_queue_get_ownership",
        "net/core/net-sysfs.c:rx_queue_get_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588506400,
      "name": "net_ns_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void net_ns_get_ownership(const struct net * net, kuid_t * uid, kgid_t * gid)
```
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
