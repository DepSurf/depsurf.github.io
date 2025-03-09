# Function: <code>__neigh_ifdown</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588048800,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:351",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588048800,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588360480,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:351",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588360480,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566912,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566912,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589418752,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418752,
      "name": "__neigh_ifdown.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589419504,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:350",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589419504,
      "name": "__neigh_ifdown.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589315936,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:354",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589315936,
      "name": "__neigh_ifdown.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590045056,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:354",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590045056,
      "name": "__neigh_ifdown.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591588512,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:397",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591588512,
      "name": "__neigh_ifdown.isra.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593369072,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:434",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593369072,
      "name": "__neigh_ifdown.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593831248,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:434",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593831248,
      "name": "__neigh_ifdown.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594612848,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:442",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594612848,
      "name": "__neigh_ifdown.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502101632,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502101632,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234853776,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234853776,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295567712,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295567712,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278378142,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278378142,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588173648,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588173648,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587886480,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587886480,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588505472,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588505472,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "__neigh_ifdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588642576,
      "name": "__neigh_ifdown",
      "external": false,
      "loc": "net/core/neighbour.c:348",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_carrier_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642576,
      "name": "__neigh_ifdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __neigh_ifdown(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
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
