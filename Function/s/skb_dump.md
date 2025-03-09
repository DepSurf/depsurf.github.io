# Function: <code>skb_dump</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588212007,
      "name": "skb_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1059
    },
    {
      "addr": 18446744071588180896,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588416771,
      "name": "skb_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1178
    },
    {
      "addr": 18446744071588386720,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:717",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283114,
      "name": "skb_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
    },
    {
      "addr": 18446744071589240848,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591625923,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:731",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591625923,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591569308,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:779",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591569308,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1098
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592692772,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:795",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:netdev_rx_csum_fault",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592692772,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1098
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594578400,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:800",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:netdev_rx_csum_fault",
        "net/core/dev.c:skb_checksum_help",
        "net/core/dev.c:skb_checksum_help",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594578400,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1172
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593144592,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:978",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:netdev_rx_csum_fault",
        "net/core/dev.c:skb_checksum_help",
        "net/core/dev.c:skb_checksum_help",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593144592,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1362
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593598176,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:1118",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_checksum_help",
        "net/core/dev.c:skb_checksum_help",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593598176,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1396
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594372768,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:1204",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_checksum_help",
        "net/core/dev.c:skb_checksum_help",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594372768,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1403
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501904120,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501904120,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234660332,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234660332,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1248
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295300800,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295300800,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1380
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
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278208706,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278208706,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1018
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023555,
      "name": "skb_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1178
    },
    {
      "addr": 18446744071587993504,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736643,
      "name": "skb_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1178
    },
    {
      "addr": 18446744071587706608,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588355331,
      "name": "skb_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1178
    },
    {
      "addr": 18446744071588325280,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```

```json
{
  "name": "skb_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_dump",
      "external": true,
      "loc": "net/core/skbuff.c:718",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_dump",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588490851,
      "name": "skb_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1239
    },
    {
      "addr": 18446744071588460704,
      "name": "skb_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void skb_dump(const char * level, const struct sk_buff * skb, bool full_pkt)
```
</details>
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
