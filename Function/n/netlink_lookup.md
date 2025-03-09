# Function: <code>netlink_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586495968,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:1066",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_getsockbyportid",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586495968,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586942112,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:452",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942112,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587137648,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:459",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587137648,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587268688,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:490",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587268688,
      "name": "netlink_lookup",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587788496,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:492",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587788496,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588130208,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:526",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588130208,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588312736,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:526",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312736,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588710736,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710736,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588934640,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934640,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589824523,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
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
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589862155,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:518",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
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
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589768183,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:528",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
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
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590527483,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:528",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
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
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592139306,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593963530,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594339114,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595138458,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:530",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502529864,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502529864,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235239664,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235239664,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296105824,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296105824,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278699594,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588541024,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588541024,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588253024,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588253024,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588873200,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588873200,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```

```json
{
  "name": "netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589014368,
      "name": "netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:517",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589014368,
      "name": "netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct sock * netlink_lookup(struct net * net, int protocol, u32 portid)
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
