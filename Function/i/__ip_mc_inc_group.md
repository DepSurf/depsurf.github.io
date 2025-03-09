# Function: <code>__ip_mc_inc_group</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, unsigned int mode)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588472128,
      "name": "__ip_mc_inc_group",
      "external": false,
      "loc": "net/ipv4/igmp.c:1390",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv4/igmp.c:ip_mc_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472128,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, unsigned int mode)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588665984,
      "name": "__ip_mc_inc_group",
      "external": false,
      "loc": "net/ipv4/igmp.c:1403",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:__ip_mc_join_group",
        "net/ipv4/igmp.c:ip_mc_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588665984,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589083599,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589081056,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589307759,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589305216,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590284927,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1468",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590279488,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590337935,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1468",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332448,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590253791,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1475",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590248016,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591037887,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1475",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591031888,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592685743,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1482",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592679536,
      "name": "__ip_mc_inc_group",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594554255,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1482",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594549344,
      "name": "__ip_mc_inc_group",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594946079,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1483",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594941184,
      "name": "__ip_mc_inc_group",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595758431,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1485",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595753504,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502942848,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502939408,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235633324,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235622708,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296617596,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296611456,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279029298,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279020870,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588913935,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588911392,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588625871,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588623328,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589350319,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589347776,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, gfp_t gfp)
```

```json
{
  "name": "__ip_mc_inc_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589392703,
      "name": "__ip_mc_inc_group",
      "external": true,
      "loc": "net/ipv4/igmp.c:1470",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589390128,
      "name": "__ip_mc_inc_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __ip_mc_inc_group(struct in_device * in_dev, __be32 addr, unsigned int mode)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int mode</code>
</li>
</ul>
</details>
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
