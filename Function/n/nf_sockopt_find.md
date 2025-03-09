# Function: <code>nf_sockopt_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nf_sockopt_ops * nf_sockopt_find(struct sock * sk, u_int8_t pf, int val, int get)
```

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586524128,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:61",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586524128,
      "name": "nf_sockopt_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586966768,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:61",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586966768,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587161568,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:61",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587161568,
      "name": "nf_sockopt_find.constprop.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587292880,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:61",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587292880,
      "name": "nf_sockopt_find.constprop.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587814544,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814544,
      "name": "nf_sockopt_find.constprop.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588157824,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588157824,
      "name": "nf_sockopt_find.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588341008,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588341008,
      "name": "nf_sockopt_find.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588741248,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588741248,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588964976,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964976,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589920192,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589920192,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589961136,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589961136,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589875904,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589875904,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590639536,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590639536,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592263488,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592263488,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594098144,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594098144,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594483296,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594483296,
      "name": "nf_sockopt_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595285520,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595285520,
      "name": "nf_sockopt_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502567808,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502567808,
      "name": "nf_sockopt_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235274116,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235274116,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296150832,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296150832,
      "name": "nf_sockopt_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278726106,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278726106,
      "name": "nf_sockopt_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588571360,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588571360,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588283344,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283344,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588903536,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588903536,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_sockopt_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589046096,
      "name": "nf_sockopt_find",
      "external": false,
      "loc": "net/netfilter/nf_sockopt.c:62",
      "file": "net/netfilter/nf_sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_sockopt.c:compat_nf_getsockopt",
        "net/netfilter/nf_sockopt.c:compat_nf_setsockopt",
        "net/netfilter/nf_sockopt.c:nf_getsockopt",
        "net/netfilter/nf_sockopt.c:nf_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589046096,
      "name": "nf_sockopt_find.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct nf_sockopt_ops * nf_sockopt_find(struct sock * sk, u_int8_t pf, int val, int get)
```
</details>
</li>
</ul>
