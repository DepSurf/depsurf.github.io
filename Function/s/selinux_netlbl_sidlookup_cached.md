# Function: <code>selinux_netlbl_sidlookup_cached</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582372432,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:56",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb"
      ],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582372432,
      "name": "selinux_netlbl_sidlookup_cached.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582595457,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:56",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582688673,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:56",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582781313,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:57",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582937457,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:57",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583135520,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:55",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135520,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583251536,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:56",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251536,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583438576,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583438576,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583544480,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583544480,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583896803,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584016883,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584044883,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584416083,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585043949,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:43",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585763101,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:43",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585993682,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:43",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586241027,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:43",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495316616,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495316616,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228694304,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228694304,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289306624,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289306624,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274532942,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274532942,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583513216,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583513216,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583450272,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450272,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583496992,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583496992,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "selinux_netlbl_sidlookup_cached",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583593360,
      "name": "selinux_netlbl_sidlookup_cached",
      "external": false,
      "loc": "security/selinux/netlabel.c:42",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593360,
      "name": "selinux_netlbl_sidlookup_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr, u32 * sid)
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
