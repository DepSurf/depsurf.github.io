# Function: <code>remove_nh_grp_entry</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589155573,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:695",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589379669,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:697",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void remove_nh_grp_entry(struct net * net, struct nh_grp_entry * nhge, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590365232,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:783",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590365232,
      "name": "remove_nh_grp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
void remove_nh_grp_entry(struct net * net, struct nh_grp_entry * nhge, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:911",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590422112,
      "name": "remove_nh_grp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071591635459,
      "name": "remove_nh_grp_entry.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void remove_nh_grp_entry(struct net * net, struct nh_grp_entry * nhge, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1732",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590345872,
      "name": "remove_nh_grp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071591578876,
      "name": "remove_nh_grp_entry.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void remove_nh_grp_entry(struct net * net, struct nh_grp_entry * nhge, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1732",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591135616,
      "name": "remove_nh_grp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
    },
    {
      "addr": 18446744071592731866,
      "name": "remove_nh_grp_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void remove_nh_grp_entry(struct net * net, struct nh_grp_entry * nhge, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1733",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592790096,
      "name": "remove_nh_grp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    },
    {
      "addr": 18446744071594618321,
      "name": "remove_nh_grp_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void remove_nh_grp_entry(struct net * net, struct nh_grp_entry * nhge, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1733",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594664064,
      "name": "remove_nh_grp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
    },
    {
      "addr": 18446744071596353114,
      "name": "remove_nh_grp_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void remove_nh_grp_entry(struct net * net, struct nh_grp_entry * nhge, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1733",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595056432,
      "name": "remove_nh_grp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
    },
    {
      "addr": 18446744071596881938,
      "name": "remove_nh_grp_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void remove_nh_grp_entry(struct net * net, struct nh_grp_entry * nhge, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1756",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595869440,
      "name": "remove_nh_grp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
    },
    {
      "addr": 18446744071597806110,
      "name": "remove_nh_grp_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503022028,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:697",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235712072,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:697",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296718404,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:697",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279089290,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:697",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588985845,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:697",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588697781,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:697",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589422229,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:697",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_nh_grp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589465813,
      "name": "remove_nh_grp_entry",
      "external": false,
      "loc": "net/ipv4/nexthop.c:697",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void remove_nh_grp_entry(struct net * net, struct nh_grp_entry * nhge, struct nl_info * nlinfo)
```
</details>
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
