# Function: <code>xsk_generic_xmit</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589118302,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:209",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589352257,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:221",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589808541,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:231",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590028302,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:338",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_sendmsg"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int xsk_generic_xmit(struct sock * sk)
```

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591065552,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:329",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591065552,
      "name": "xsk_generic_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
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
int xsk_generic_xmit(struct sock * sk)
```

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591128672,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:433",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591128672,
      "name": "xsk_generic_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
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
int xsk_generic_xmit(struct sock * sk)
```

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591058816,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:539",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591058816,
      "name": "xsk_generic_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
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
int xsk_generic_xmit(struct sock * sk)
```

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:539",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591900928,
      "name": "xsk_generic_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
    },
    {
      "addr": 18446744071592751155,
      "name": "xsk_generic_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int xsk_generic_xmit(struct sock * sk)
```

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:514",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593623136,
      "name": "xsk_generic_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1371
    },
    {
      "addr": 18446744071594637888,
      "name": "xsk_generic_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595555061,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:597",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_poll"
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
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596062901,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:598",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_poll"
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
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596930549,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:871",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_poll"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503779524,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:338",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_sendmsg"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236402712,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:338",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_sendmsg"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297624716,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:338",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_sendmsg"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279692624,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:338",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_sendmsg"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589631902,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:338",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_sendmsg"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589356430,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:338",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_sendmsg"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590073934,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:338",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_sendmsg"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_generic_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590128912,
      "name": "xsk_generic_xmit",
      "external": false,
      "loc": "net/xdp/xsk.c:338",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int xsk_generic_xmit(struct sock * sk)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int xsk_generic_xmit(struct sock * sk)
```
</details>
</li>
</ul>
