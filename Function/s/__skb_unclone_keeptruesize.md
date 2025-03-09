# Function: <code>__skb_unclone_keeptruesize</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __skb_unclone_keeptruesize(struct sk_buff * skb, gfp_t pri)
```

```json
{
  "name": "__skb_unclone_keeptruesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591418400,
      "name": "__skb_unclone_keeptruesize",
      "external": true,
      "loc": "net/core/skbuff.c:1786",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591418400,
      "name": "__skb_unclone_keeptruesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int __skb_unclone_keeptruesize(struct sk_buff * skb, gfp_t pri)
```

```json
{
  "name": "__skb_unclone_keeptruesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593191264,
      "name": "__skb_unclone_keeptruesize",
      "external": true,
      "loc": "net/core/skbuff.c:1989",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593191264,
      "name": "__skb_unclone_keeptruesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int __skb_unclone_keeptruesize(struct sk_buff * skb, gfp_t pri)
```

```json
{
  "name": "__skb_unclone_keeptruesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_unclone_keeptruesize",
      "external": true,
      "loc": "net/core/skbuff.c:2139",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596852076,
      "name": "__skb_unclone_keeptruesize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593649744,
      "name": "__skb_unclone_keeptruesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __skb_unclone_keeptruesize(struct sk_buff * skb, gfp_t pri)
```

```json
{
  "name": "__skb_unclone_keeptruesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_unclone_keeptruesize",
      "external": true,
      "loc": "net/core/skbuff.c:2227",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597776962,
      "name": "__skb_unclone_keeptruesize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594425520,
      "name": "__skb_unclone_keeptruesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __skb_unclone_keeptruesize(struct sk_buff * skb, gfp_t pri)
```
</details>
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
