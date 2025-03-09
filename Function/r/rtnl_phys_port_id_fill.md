# Function: <code>rtnl_phys_port_id_fill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586374892,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:990",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586807334,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1023",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586995114,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1032",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587120441,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1031",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587624492,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1006",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587936195,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1098",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588059840,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588059840,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588375216,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588375216,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588581616,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588581616,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589433088,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1133",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589433088,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589433584,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1145",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589433584,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589330944,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1147",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589330944,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590060368,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1136",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590060368,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591642908,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1176",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593425867,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1187",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593891426,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1195",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594674584,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1203",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502127400,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502127400,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234871500,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234871500,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295589760,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295589760,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278390296,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278390296,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588188352,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588188352,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587901184,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587901184,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588520176,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588520176,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_phys_port_id_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588657440,
      "name": "rtnl_phys_port_id_fill",
      "external": false,
      "loc": "net/core/rtnetlink.c:1111",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588657440,
      "name": "rtnl_phys_port_id_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int rtnl_phys_port_id_fill(struct sk_buff * skb, struct net_device * dev)
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
