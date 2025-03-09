# Function: <code>fib6_nh_release_dsts</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh * fib6_nh)
```

```json
{
  "name": "fib6_nh_release_dsts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591482320,
      "name": "fib6_nh_release_dsts",
      "external": true,
      "loc": "net/ipv6/route.c:3683",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591482320,
      "name": "fib6_nh_release_dsts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh * fib6_nh)
```

```json
{
  "name": "fib6_nh_release_dsts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593165696,
      "name": "fib6_nh_release_dsts",
      "external": true,
      "loc": "net/ipv6/route.c:3659",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_release"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593123872,
      "name": "fib6_nh_release_dsts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071593165760,
      "name": "fib6_nh_release_dsts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh * fib6_nh)
```

```json
{
  "name": "fib6_nh_release_dsts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595063808,
      "name": "fib6_nh_release_dsts",
      "external": true,
      "loc": "net/ipv6/route.c:3659",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_release"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595022080,
      "name": "fib6_nh_release_dsts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071595063888,
      "name": "fib6_nh_release_dsts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh * fib6_nh)
```

```json
{
  "name": "fib6_nh_release_dsts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595457408,
      "name": "fib6_nh_release_dsts",
      "external": true,
      "loc": "net/ipv6/route.c:3657",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_release"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595415584,
      "name": "fib6_nh_release_dsts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071595457488,
      "name": "fib6_nh_release_dsts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh * fib6_nh)
```

```json
{
  "name": "fib6_nh_release_dsts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596299520,
      "name": "fib6_nh_release_dsts",
      "external": true,
      "loc": "net/ipv6/route.c:3659",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_release"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596257392,
      "name": "fib6_nh_release_dsts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071596299600,
      "name": "fib6_nh_release_dsts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh * fib6_nh)
```
</details>
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
