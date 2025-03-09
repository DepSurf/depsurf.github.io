# Function: <code>nf_route</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588158688,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:53",
      "file": "net/netfilter/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588158688,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588342656,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:162",
      "file": "net/netfilter/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588342656,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588742992,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588742992,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966720,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966720,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589921952,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589921952,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589962608,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589962608,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589877344,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589877344,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590640976,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590640976,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592265120,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592265120,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594099888,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594099888,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594485056,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594485056,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595287280,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595287280,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502569944,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502569944,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235275604,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235275604,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296153664,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296153664,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278727552,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278727552,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588573104,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588573104,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588285088,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588285088,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588905280,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588905280,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```

```json
{
  "name": "nf_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589047840,
      "name": "nf_route",
      "external": true,
      "loc": "net/netfilter/utils.c:163",
      "file": "net/netfilter/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589047840,
      "name": "nf_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int nf_route(struct net * net, struct dst_entry * * dst, struct flowi * fl, bool strict, short unsigned int family)
```
</details>
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
