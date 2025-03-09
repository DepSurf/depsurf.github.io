# Function: <code>rcu_segcblist_xchg_len</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```

```json
{
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071475,
      "name": "rcu_segcblist_xchg_len",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:137",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070064,
      "name": "rcu_segcblist_xchg_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580130141,
      "name": "rcu_segcblist_xchg_len",
      "external": false,
      "loc": "kernel/rcu/rcu_segcblist.c:128",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
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
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580108365,
      "name": "rcu_segcblist_xchg_len",
      "external": false,
      "loc": "kernel/rcu/rcu_segcblist.c:128",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```

```json
{
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491284632,
      "name": "rcu_segcblist_xchg_len",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:137",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491282608,
      "name": "rcu_segcblist_xchg_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```

```json
{
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225291736,
      "name": "rcu_segcblist_xchg_len",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:137",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225289752,
      "name": "rcu_segcblist_xchg_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```

```json
{
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284189428,
      "name": "rcu_segcblist_xchg_len",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:137",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284187568,
      "name": "rcu_segcblist_xchg_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```

```json
{
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801618,
      "name": "rcu_segcblist_xchg_len",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:137",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271800146,
      "name": "rcu_segcblist_xchg_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```

```json
{
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040211,
      "name": "rcu_segcblist_xchg_len",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:137",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038800,
      "name": "rcu_segcblist_xchg_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```

```json
{
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985553,
      "name": "rcu_segcblist_xchg_len",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:137",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984208,
      "name": "rcu_segcblist_xchg_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```

```json
{
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031747,
      "name": "rcu_segcblist_xchg_len",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:137",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030336,
      "name": "rcu_segcblist_xchg_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```

```json
{
  "name": "rcu_segcblist_xchg_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082451,
      "name": "rcu_segcblist_xchg_len",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:137",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081040,
      "name": "rcu_segcblist_xchg_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
long int rcu_segcblist_xchg_len(struct rcu_segcblist * rsclp, long int v)
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
