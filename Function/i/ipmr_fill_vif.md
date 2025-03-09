# Function: <code>ipmr_fill_vif</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587670911,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2673",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588197127,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2838",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588551359,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2667",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588746559,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2708",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589178563,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2771",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589403512,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2772",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool ipmr_fill_vif(struct mr_table * mrt, u32 vifid, struct sk_buff * skb)
```

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590391536,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2740",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590391536,
      "name": "ipmr_fill_vif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
bool ipmr_fill_vif(struct mr_table * mrt, u32 vifid, struct sk_buff * skb)
```

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590445120,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2749",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590445120,
      "name": "ipmr_fill_vif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
bool ipmr_fill_vif(struct mr_table * mrt, u32 vifid, struct sk_buff * skb)
```

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590370384,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2749",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590370384,
      "name": "ipmr_fill_vif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
bool ipmr_fill_vif(struct mr_table * mrt, u32 vifid, struct sk_buff * skb)
```

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591161488,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2751",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591161488,
      "name": "ipmr_fill_vif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
bool ipmr_fill_vif(struct mr_table * mrt, u32 vifid, struct sk_buff * skb)
```

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592819728,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2745",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592819728,
      "name": "ipmr_fill_vif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 693
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
bool ipmr_fill_vif(struct mr_table * mrt, u32 vifid, struct sk_buff * skb)
```

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594696176,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2752",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594696176,
      "name": "ipmr_fill_vif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
bool ipmr_fill_vif(struct mr_table * mrt, u32 vifid, struct sk_buff * skb)
```

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595088096,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2767",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595088096,
      "name": "ipmr_fill_vif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
bool ipmr_fill_vif(struct mr_table * mrt, u32 vifid, struct sk_buff * skb)
```

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595901216,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2765",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595901216,
      "name": "ipmr_fill_vif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503042544,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2772",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235733960,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2772",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296751352,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2772",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279115052,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2772",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589008587,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2772",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588731643,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2772",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589444971,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2772",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_fill_vif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589489800,
      "name": "ipmr_fill_vif",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2772",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool ipmr_fill_vif(struct mr_table * mrt, u32 vifid, struct sk_buff * skb)
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
