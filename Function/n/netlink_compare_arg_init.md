# Function: <code>netlink_compare_arg_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586494567,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:1038",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_lookup",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586940999,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:424",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587136247,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:431",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587261584,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:462",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587261584,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587780976,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:464",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587780976,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588123408,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:498",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123408,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588305664,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:498",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588305664,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588703568,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703568,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588927440,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588927440,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589821819,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589858379,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:490",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589765845,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:500",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590525140,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:500",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592133361,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:504",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594597273,
      "name": "netlink_compare_arg_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593959121,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:504",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594324160,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:504",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594324160,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595123728,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:502",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595123728,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502520968,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502520968,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235241844,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_autobind",
        "net/netlink/af_netlink.c:netlink_lookup",
        "net/netlink/af_netlink.c:__netlink_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296093648,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296093648,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278694272,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588533824,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588533824,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245824,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245824,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588866000,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866000,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```

```json
{
  "name": "netlink_compare_arg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589007488,
      "name": "netlink_compare_arg_init",
      "external": false,
      "loc": "net/netlink/af_netlink.c:489",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_hash",
        "net/netlink/af_netlink.c:netlink_lookup",
        "net/netlink/af_netlink.c:__netlink_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589007488,
      "name": "netlink_compare_arg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
```
</details>
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
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
void netlink_compare_arg_init(struct netlink_compare_arg * arg, struct net * net, u32 portid)
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
