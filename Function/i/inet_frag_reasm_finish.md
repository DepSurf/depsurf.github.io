# Function: <code>inet_frag_reasm_finish</code>

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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130352,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130352,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589354512,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354512,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590335264,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590335264,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590387840,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:508",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590387840,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590304144,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:508",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590304144,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:510",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592729316,
      "name": "inet_frag_reasm_finish.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071591091536,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:510",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594615757,
      "name": "inet_frag_reasm_finish.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071592742384,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:516",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596350614,
      "name": "inet_frag_reasm_finish.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071594613632,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:516",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596879566,
      "name": "inet_frag_reasm_finish.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071595005584,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:516",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597803695,
      "name": "inet_frag_reasm_finish.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071595818256,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502995920,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502995920,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235685180,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235685180,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296684736,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296684736,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279071092,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279071092,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588960688,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588960688,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588672624,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588672624,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397072,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397072,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
```

```json
{
  "name": "inet_frag_reasm_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589440160,
      "name": "inet_frag_reasm_finish",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:477",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589440160,
      "name": "inet_frag_reasm_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void inet_frag_reasm_finish(struct inet_frag_queue * q, struct sk_buff * head, void * reasm_data, bool try_coalesce)
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
