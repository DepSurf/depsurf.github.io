# Function: <code>__xfrm_mode_tunnel_prep</code>

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
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589299008,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589299008,
      "name": "__xfrm_mode_tunnel_prep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589523360,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589523360,
      "name": "__xfrm_mode_tunnel_prep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590517104,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:34",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep",
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590517104,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590576960,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:34",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep",
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590576960,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590502848,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:34",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep",
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590502848,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591308464,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:34",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep",
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591308464,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592975936,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:34",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep",
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592975936,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594863728,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:34",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep",
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594863728,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595255232,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:35",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep",
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595255232,
      "name": "__xfrm_mode_tunnel_prep",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596095664,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:35",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep",
        "net/xfrm/xfrm_device.c:xfrm_outer_mode_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596095664,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503188696,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503188696,
      "name": "__xfrm_mode_tunnel_prep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235864352,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235864352,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296919744,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296919744,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279229244,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279229244,
      "name": "__xfrm_mode_tunnel_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589127728,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589127728,
      "name": "__xfrm_mode_tunnel_prep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588852752,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588852752,
      "name": "__xfrm_mode_tunnel_prep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589564592,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589564592,
      "name": "__xfrm_mode_tunnel_prep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xfrm_mode_tunnel_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589612256,
      "name": "__xfrm_mode_tunnel_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:36",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589612256,
      "name": "__xfrm_mode_tunnel_prep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state * x, struct sk_buff * skb, unsigned int hsize)
```
</details>
</li>
</ul>
