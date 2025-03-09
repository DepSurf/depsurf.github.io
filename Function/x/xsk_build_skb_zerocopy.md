# Function: <code>xsk_build_skb_zerocopy</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * xsk_build_skb_zerocopy(struct xdp_sock * xs, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_build_skb_zerocopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591055856,
      "name": "xsk_build_skb_zerocopy",
      "external": false,
      "loc": "net/xdp/xsk.c:448",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591055856,
      "name": "xsk_build_skb_zerocopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
struct sk_buff * xsk_build_skb_zerocopy(struct xdp_sock * xs, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_build_skb_zerocopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_build_skb_zerocopy",
      "external": false,
      "loc": "net/xdp/xsk.c:448",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591898480,
      "name": "xsk_build_skb_zerocopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
    },
    {
      "addr": 18446744071592751053,
      "name": "xsk_build_skb_zerocopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
struct sk_buff * xsk_build_skb_zerocopy(struct xdp_sock * xs, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_build_skb_zerocopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_build_skb_zerocopy",
      "external": false,
      "loc": "net/xdp/xsk.c:423",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593622432,
      "name": "xsk_build_skb_zerocopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
    },
    {
      "addr": 18446744071594637853,
      "name": "xsk_build_skb_zerocopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
struct sk_buff * xsk_build_skb_zerocopy(struct xdp_sock * xs, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_build_skb_zerocopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_build_skb_zerocopy",
      "external": false,
      "loc": "net/xdp/xsk.c:423",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595552064,
      "name": "xsk_build_skb_zerocopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
    },
    {
      "addr": 18446744071596367283,
      "name": "xsk_build_skb_zerocopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
struct sk_buff * xsk_build_skb_zerocopy(struct xdp_sock * xs, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_build_skb_zerocopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_build_skb_zerocopy",
      "external": false,
      "loc": "net/xdp/xsk.c:424",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596059840,
      "name": "xsk_build_skb_zerocopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071596896997,
      "name": "xsk_build_skb_zerocopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
struct sk_buff * xsk_build_skb_zerocopy(struct xdp_sock * xs, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_build_skb_zerocopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_build_skb_zerocopy",
      "external": false,
      "loc": "net/xdp/xsk.c:613",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596926608,
      "name": "xsk_build_skb_zerocopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 846
    },
    {
      "addr": 18446744071597822329,
      "name": "xsk_build_skb_zerocopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct sk_buff * xsk_build_skb_zerocopy(struct xdp_sock * xs, struct xdp_desc * desc)
```
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
