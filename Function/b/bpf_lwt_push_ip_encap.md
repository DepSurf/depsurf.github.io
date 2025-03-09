# Function: <code>bpf_lwt_push_ip_encap</code>

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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588558208,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:589",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588558208,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1367
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588775248,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588775248,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1400
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589647472,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647472,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671216,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671216,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589562720,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589562720,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1235
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590307904,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590307904,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1297
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591892896,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591892896,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1348
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593695376,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593695376,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1348
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594176208,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:591",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594176208,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1351
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594972736,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:591",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594972736,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1348
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502342160,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502342160,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1208
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235081652,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235081652,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1340
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295864960,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295864960,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1492
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278563220,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278563220,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588381632,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381632,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1400
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094320,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094320,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1400
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588713808,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713808,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1400
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```

```json
{
  "name": "bpf_lwt_push_ip_encap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588854064,
      "name": "bpf_lwt_push_ip_encap",
      "external": true,
      "loc": "net/core/lwt_bpf.c:592",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_xmit_push_encap",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588854064,
      "name": "bpf_lwt_push_ip_encap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1400
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
int bpf_lwt_push_ip_encap(struct sk_buff * skb, void * hdr, u32 len, bool ingress)
```
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
