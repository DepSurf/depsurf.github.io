# Function: <code>netlbl_skbuff_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587282928,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1097",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587282928,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587749824,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1400",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587749824,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587965040,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1400",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965040,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588123168,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1400",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123168,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588670992,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1400",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670992,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589037552,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1400",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037552,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589263552,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1401",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589263552,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718816,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718816,
      "name": "netlbl_skbuff_err",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589943120,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589943120,
      "name": "netlbl_skbuff_err",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590972768,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1393",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590972768,
      "name": "netlbl_skbuff_err",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591037552,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1393",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591037552,
      "name": "netlbl_skbuff_err",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590968128,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1393",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590968128,
      "name": "netlbl_skbuff_err",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591805664,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1393",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591805664,
      "name": "netlbl_skbuff_err",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593517232,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1395",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593517232,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595437200,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1395",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595437200,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595944160,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1396",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595944160,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596805984,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1396",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596805984,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503673960,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503673960,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236311096,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236311096,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297498688,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297498688,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279610574,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279610574,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546720,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546720,
      "name": "netlbl_skbuff_err",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589271296,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589271296,
      "name": "netlbl_skbuff_err",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589988752,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589988752,
      "name": "netlbl_skbuff_err",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff * skb, u16 family, int error, int gateway)
```

```json
{
  "name": "netlbl_skbuff_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590038640,
      "name": "netlbl_skbuff_err",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1387",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_err",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590038640,
      "name": "netlbl_skbuff_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 family</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, error, gateway</code> ➡️ <code>skb, family, error, gateway</code>
</li>
</ul>
</details>
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
