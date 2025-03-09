# Function: <code>kfree_pmc</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589067472,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589067472,
      "name": "kfree_pmc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589291632,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589291632,
      "name": "kfree_pmc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590274560,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:642",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmpv3_send_cr"
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
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590327504,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:642",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmpv3_send_cr"
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
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590243472,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:642",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmpv3_send_cr"
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
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591027056,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:642",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmpv3_send_cr"
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
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592674336,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:643",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmpv3_send_cr"
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
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594542416,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:643",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmpv3_send_cr"
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
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594934208,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmpv3_send_cr"
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
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595746416,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:646",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmpv3_send_cr"
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
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502923128,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502923128,
      "name": "kfree_pmc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235616620,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235616620,
      "name": "kfree_pmc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296594560,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296594560,
      "name": "kfree_pmc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279015018,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279015018,
      "name": "kfree_pmc",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588897808,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588897808,
      "name": "kfree_pmc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588609744,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588609744,
      "name": "kfree_pmc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589334192,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589334192,
      "name": "kfree_pmc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void kfree_pmc(struct ip_mc_list * pmc)
```

```json
{
  "name": "kfree_pmc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589376304,
      "name": "kfree_pmc",
      "external": false,
      "loc": "net/ipv4/igmp.c:644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376304,
      "name": "kfree_pmc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void kfree_pmc(struct ip_mc_list * pmc)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void kfree_pmc(struct ip_mc_list * pmc)
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
