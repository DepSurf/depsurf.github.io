# Function: <code>rt6_exception_hash</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394784,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1185",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394784,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588754496,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1307",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754496,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588974736,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1321",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588974736,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589420736,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1471",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589420736,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589645056,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1477",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589645056,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590654623,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1499",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
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
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590713743,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1482",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
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
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590631392,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1485",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590631392,
      "name": "rt6_exception_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591444512,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1485",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591444512,
      "name": "rt6_exception_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593124544,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1485",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593124544,
      "name": "rt6_exception_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595020656,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1485",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595020656,
      "name": "rt6_exception_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595414160,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1484",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595414160,
      "name": "rt6_exception_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596255968,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1486",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596255968,
      "name": "rt6_exception_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503327264,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1477",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503327264,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235999884,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1477",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235999884,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297094192,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1477",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297094192,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279344210,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1477",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279344210,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
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
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589249424,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1477",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589249424,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588974416,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1477",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588974416,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589686288,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1477",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589686288,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```

```json
{
  "name": "rt6_exception_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589735616,
      "name": "rt6_exception_hash",
      "external": false,
      "loc": "net/ipv6/route.c:1477",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__rt6_find_exception_rcu",
        "net/ipv6/route.c:__rt6_find_exception_spinlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589735616,
      "name": "rt6_exception_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
u32 rt6_exception_hash(const struct in6_addr * dst, const struct in6_addr * src)
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
