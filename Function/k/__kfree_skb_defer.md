# Function: <code>__kfree_skb_defer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586212255,
      "name": "__kfree_skb_defer",
      "external": false,
      "loc": "net/core/skbuff.c:772",
      "file": "net/core/skbuff.c",
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
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586659040,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:795",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586659040,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586843920,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:795",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586843920,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586962704,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:801",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586962704,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587459936,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:753",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587459936,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587764256,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:753",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587764256,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587898176,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:757",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587898176,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588204560,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204560,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588409648,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588409648,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589274240,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:889",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589274240,
      "name": "__kfree_skb_defer",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589274240,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:901",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589274240,
      "name": "__kfree_skb_defer",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589168080,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:934",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589168080,
      "name": "__kfree_skb_defer",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589888544,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:950",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589888544,
      "name": "__kfree_skb_defer",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591417952,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:955",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action",
        "net/core/gro.c:napi_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591417952,
      "name": "__kfree_skb_defer",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593190768,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:1136",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action",
        "net/core/gro.c:napi_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593190768,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501926640,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501926640,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234685956,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234685956,
      "name": "__kfree_skb_defer",
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295344928,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295344928,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278237112,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278237112,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588016432,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016432,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587729520,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587729520,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588348208,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588348208,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __kfree_skb_defer(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb_defer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588483728,
      "name": "__kfree_skb_defer",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588483728,
      "name": "__kfree_skb_defer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __kfree_skb_defer(struct sk_buff * skb)
```
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void __kfree_skb_defer(struct sk_buff * skb)
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
