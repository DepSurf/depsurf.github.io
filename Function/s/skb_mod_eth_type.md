# Function: <code>skb_mod_eth_type</code>

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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588176208,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5450",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588176208,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588381376,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381376,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589270493,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5564",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
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
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589270342,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5699",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
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
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589160431,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5787",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
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
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589882943,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5862",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
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
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591412618,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5783",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
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
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593177690,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5985",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
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
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593635162,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:6036",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
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
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594411002,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:6189",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501892552,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501892552,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234656340,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234656340,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295318944,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295318944,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278212470,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278212470,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988160,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988160,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587701264,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587701264,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319936,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319936,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
```

```json
{
  "name": "skb_mod_eth_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588455312,
      "name": "skb_mod_eth_type",
      "external": false,
      "loc": "net/core/skbuff.c:5462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455312,
      "name": "skb_mod_eth_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
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
void skb_mod_eth_type(struct sk_buff * skb, struct ethhdr * hdr, __be16 ethertype)
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
