# Function: <code>inet_frag_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_frag_queue * inet_frag_find(struct netns_frags * nf, struct inet_frags * f, void * key, unsigned int hash)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586848480,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:399",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848480,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_frag_queue * inet_frag_find(struct netns_frags * nf, struct inet_frags * f, void * key, unsigned int hash)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587298208,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:391",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298208,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_frag_queue * inet_frag_find(struct netns_frags * nf, struct inet_frags * f, void * key, unsigned int hash)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587500272,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:391",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500272,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_frag_queue * inet_frag_find(struct netns_frags * nf, struct inet_frags * f, void * key, unsigned int hash)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587637616,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:389",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637616,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_frag_queue * inet_frag_find(struct netns_frags * nf, struct inet_frags * f, void * key, unsigned int hash)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588162208,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:392",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162208,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inet_frag_queue * inet_frag_find(struct netns_frags * nf, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588516496,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:200",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588516496,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1044
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inet_frag_queue * inet_frag_find(struct netns_frags * nf, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588712016,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:206",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588712016,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589133616,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589133616,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589357760,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589357760,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590339328,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590339328,
      "name": "inet_frag_find.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
    },
    {
      "addr": 18446744071590339856,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590392176,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:353",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590392176,
      "name": "inet_frag_find.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    },
    {
      "addr": 18446744071590392720,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590308128,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:353",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590308128,
      "name": "inet_frag_find.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
    },
    {
      "addr": 18446744071590308848,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591095536,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:353",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591095536,
      "name": "inet_frag_find.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
    },
    {
      "addr": 18446744071591096256,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592747040,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:353",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592747040,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594618464,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:359",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594618464,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595010464,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:359",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595010464,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 871
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595823184,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:359",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595823184,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 871
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502998864,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502998864,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235688720,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235688720,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296689344,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296689344,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279073874,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279073874,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588963936,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588963936,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588675872,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588675872,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589400320,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589400320,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct inet_frag_queue * inet_frag_find(struct fqdir * fqdir, void * key)
```

```json
{
  "name": "inet_frag_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589443680,
      "name": "inet_frag_find",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:322",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589443680,
      "name": "inet_frag_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct inet_frags * f</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int hash</code>
</li>
<li>
<b>Param reordered. </b>
<code>nf, f, key, hash</code> ➡️ <code>nf, key</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fqdir * fqdir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct netns_frags * nf</code>
</li>
</ul>
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
