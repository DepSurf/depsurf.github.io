# Function: <code>strp_init</code>

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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588653984,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:475",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588653984,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589020240,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:456",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589020240,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245568,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:456",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245568,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589700688,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589700688,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589925024,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589925024,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590954160,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp",
        "net/xfrm/espintcp.c:espintcp_init_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590954160,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591018752,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp",
        "net/xfrm/espintcp.c:espintcp_init_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591018752,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590949312,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp",
        "net/xfrm/espintcp.c:espintcp_init_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590949312,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591785568,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:440",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp",
        "net/xfrm/espintcp.c:espintcp_init_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591785568,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593495088,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:440",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp",
        "net/xfrm/espintcp.c:espintcp_init_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593495088,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595413424,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:440",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp",
        "net/xfrm/espintcp.c:espintcp_init_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595413424,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595919584,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:440",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp",
        "net/xfrm/espintcp.c:espintcp_init_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595919584,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596780640,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:440",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp",
        "net/xfrm/espintcp.c:espintcp_init_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596780640,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503651424,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503651424,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236292672,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236292672,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297471824,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297471824,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279594050,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279594050,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589529392,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589529392,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589255456,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255456,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589970656,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589970656,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
```

```json
{
  "name": "strp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590020288,
      "name": "strp_init",
      "external": true,
      "loc": "net/strparser/strparser.c:448",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_init_strp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590020288,
      "name": "strp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int strp_init(struct strparser * strp, struct sock * sk, const struct strp_callbacks * cb)
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
