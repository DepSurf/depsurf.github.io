# Function: <code>strp_done</code>

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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588654416,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:530",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_gc_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654416,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589020672,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:524",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_gc_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589020672,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246000,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:524",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246000,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589703061,
      "name": "strp_done.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071589701120,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589925456,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589925456,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590954592,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/xfrm/espintcp.c:espintcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590954592,
      "name": "strp_done",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591019184,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/xfrm/espintcp.c:espintcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591019184,
      "name": "strp_done",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590949744,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/xfrm/espintcp.c:espintcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590949744,
      "name": "strp_done",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591786000,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:508",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/xfrm/espintcp.c:espintcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591786000,
      "name": "strp_done",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593495552,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:508",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/xfrm/espintcp.c:espintcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593495552,
      "name": "strp_done",
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595413936,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:508",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/xfrm/espintcp.c:espintcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595413936,
      "name": "strp_done",
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595920096,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:508",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/xfrm/espintcp.c:espintcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595920096,
      "name": "strp_done",
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596781152,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:508",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/xfrm/espintcp.c:espintcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596781152,
      "name": "strp_done",
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503651840,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503651840,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236293076,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236293076,
      "name": "strp_done",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297472416,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297472416,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279594402,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279594402,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589529824,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589529824,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589255888,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255888,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589971088,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589971088,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void strp_done(struct strparser * strp)
```

```json
{
  "name": "strp_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590020720,
      "name": "strp_done",
      "external": true,
      "loc": "net/strparser/strparser.c:516",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590020720,
      "name": "strp_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void strp_done(struct strparser * strp)
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
