# Function: <code>__skb_zcopy_downgrade_managed</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __skb_zcopy_downgrade_managed(struct sk_buff * skb)
```

```json
{
  "name": "__skb_zcopy_downgrade_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593150144,
      "name": "__skb_zcopy_downgrade_managed",
      "external": true,
      "loc": "net/core/skbuff.c:1562",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_sg_from_iter_iovec",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593150144,
      "name": "__skb_zcopy_downgrade_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void __skb_zcopy_downgrade_managed(struct sk_buff * skb)
```

```json
{
  "name": "__skb_zcopy_downgrade_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593604272,
      "name": "__skb_zcopy_downgrade_managed",
      "external": true,
      "loc": "net/core/skbuff.c:1706",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_sg_from_iter_iovec",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593604272,
      "name": "__skb_zcopy_downgrade_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void __skb_zcopy_downgrade_managed(struct sk_buff * skb)
```

```json
{
  "name": "__skb_zcopy_downgrade_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594379600,
      "name": "__skb_zcopy_downgrade_managed",
      "external": true,
      "loc": "net/core/skbuff.c:1794",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_sg_from_iter_iovec",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594379600,
      "name": "__skb_zcopy_downgrade_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void __skb_zcopy_downgrade_managed(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
