# Function: <code>clean_xps_maps</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587954544,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2206",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587954544,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588265712,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2216",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588265712,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588472032,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2134",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472032,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589336160,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2494",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589336160,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589336976,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2519",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589336976,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
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
void clean_xps_maps(struct net_device * dev, enum xps_map_type type, u16 offset, u16 count)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589233920,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2583",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589233920,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
void clean_xps_maps(struct net_device * dev, enum xps_map_type type, u16 offset, u16 count)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589958912,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2458",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589958912,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
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
void clean_xps_maps(struct net_device * dev, enum xps_map_type type, u16 offset, u16 count)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591495168,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2435",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591495168,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
void clean_xps_maps(struct net_device * dev, enum xps_map_type type, u16 offset, u16 count)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593263536,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2420",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593263536,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
void clean_xps_maps(struct net_device * dev, enum xps_map_type type, u16 offset, u16 count)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593721168,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2446",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593721168,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
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
void clean_xps_maps(struct net_device * dev, enum xps_map_type type, u16 offset, u16 count)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594502448,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2449",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594502448,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501992056,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2134",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501992056,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234763360,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2134",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234763360,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295432768,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2134",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295432768,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278302010,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2134",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278302010,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588078816,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2134",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588078816,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587792384,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2134",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587792384,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588410592,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2134",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588410592,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
```

```json
{
  "name": "clean_xps_maps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588549184,
      "name": "clean_xps_maps",
      "external": false,
      "loc": "net/core/dev.c:2134",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549184,
      "name": "clean_xps_maps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void clean_xps_maps(struct net_device * dev, const long unsigned int * mask, struct xps_dev_maps * dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum xps_map_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>const long unsigned int * mask</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xps_dev_maps * dev_maps</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_ids</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_rxqs_map</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, mask, dev_maps, nr_ids, offset, count, is_rxqs_map</code> ➡️ <code>dev, type, offset, count</code>
</li>
</ul>
</details>
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
