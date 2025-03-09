# Function: <code>skb_defer_rx_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_defer_rx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:2987",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_defer_rx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3194",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_defer_rx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3246",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_defer_rx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3320",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_defer_rx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3504",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588048272,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:58",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588048272,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588216544,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:58",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216544,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588550592,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588550592,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588767440,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767440,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589639216,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589639216,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589662800,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589662800,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589554384,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589554384,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590299168,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299168,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591882592,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591882592,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593684208,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593684208,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594164880,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594164880,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594961440,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594961440,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502332616,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502332616,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235072904,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235072904,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295851648,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295851648,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278555206,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278555206,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_defer_rx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3775",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_defer_rx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3775",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588706000,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588706000,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_defer_rx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588845920,
      "name": "skb_defer_rx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:45",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845920,
      "name": "skb_defer_rx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool skb_defer_rx_timestamp(struct sk_buff * skb)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
