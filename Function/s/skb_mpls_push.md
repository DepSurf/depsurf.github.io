# Function: <code>skb_mpls_push</code>

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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588192944,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5473",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588192944,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588398128,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5486",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588398128,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5591",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284485,
      "name": "skb_mpls_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589266736,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5726",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591627262,
      "name": "skb_mpls_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589266048,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5814",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591570643,
      "name": "skb_mpls_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589153728,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5889",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694363,
      "name": "skb_mpls_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589874000,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594580027,
      "name": "skb_mpls_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591405936,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593170944,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:6012",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593170944,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593624320,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:6063",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593624320,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594399648,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:6216",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594399648,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501914152,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5486",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501914152,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234674820,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5486",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234674820,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295329024,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5486",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295329024,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278226638,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5486",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278226638,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588004912,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5486",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588004912,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718000,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5486",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718000,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588336688,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5486",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588336688,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet)
```

```json
{
  "name": "skb_mpls_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588472160,
      "name": "skb_mpls_push",
      "external": true,
      "loc": "net/core/skbuff.c:5486",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472160,
      "name": "skb_mpls_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int skb_mpls_push(struct sk_buff * skb, __be32 mpls_lse, __be16 mpls_proto)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int mac_len</code>
</li>
<li>
<b>Param added. </b>
<code>bool ethernet</code>
</li>
</ul>
</details>
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
