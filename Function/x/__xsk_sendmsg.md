# Function: <code>__xsk_sendmsg</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590028144,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:404",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590028144,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 915
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591066368,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:398",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591066368,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591130576,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:521",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591130576,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591061408,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:614",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591061408,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:614",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591904256,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071592751299,
      "name": "__xsk_sendmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593625067,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:630",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_sendmsg"
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
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:631",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595554176,
      "name": "__xsk_sendmsg.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446744071596367355,
      "name": "__xsk_sendmsg.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:632",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596062016,
      "name": "__xsk_sendmsg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446744071596897071,
      "name": "__xsk_sendmsg.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:905",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596929744,
      "name": "__xsk_sendmsg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
    },
    {
      "addr": 18446744071597822426,
      "name": "__xsk_sendmsg.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503779392,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:404",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503779392,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236402568,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:404",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236402568,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
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
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297624528,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:404",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297624528,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
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
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279692506,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:404",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279692506,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589631744,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:404",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589631744,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 915
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
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589356272,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:404",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589356272,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 915
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
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590073776,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:404",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590073776,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 915
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
int __xsk_sendmsg(struct sock * sk)
```

```json
{
  "name": "__xsk_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590128816,
      "name": "__xsk_sendmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:404",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_poll",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590128816,
      "name": "__xsk_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int __xsk_sendmsg(struct sock * sk)
```
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __xsk_sendmsg(struct sock * sk)
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
