# Function: <code>netif_receive_skb_list_internal</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587987231,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5191",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list"
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
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588299119,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5217",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588500112,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5119",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500112,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372048,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5502",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372048,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589377584,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5559",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589377584,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589272176,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5683",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589272176,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589999504,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5653",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589999504,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591541392,
      "name": "netif_receive_skb_list_internal",
      "external": true,
      "loc": "net/core/dev.c:5690",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591541392,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593314912,
      "name": "netif_receive_skb_list_internal",
      "external": true,
      "loc": "net/core/dev.c:5681",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593314912,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593776576,
      "name": "netif_receive_skb_list_internal",
      "external": true,
      "loc": "net/core/dev.c:5657",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593776576,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594557024,
      "name": "netif_receive_skb_list_internal",
      "external": true,
      "loc": "net/core/dev.c:5739",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594557024,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502031672,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5119",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502031672,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234783764,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5119",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234783764,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295475952,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5119",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295475952,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278320998,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5119",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278320998,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588106864,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5119",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588106864,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587819744,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5119",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587819744,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588438672,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5119",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438672,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
void netif_receive_skb_list_internal(struct list_head * head)
```

```json
{
  "name": "netif_receive_skb_list_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588575280,
      "name": "netif_receive_skb_list_internal",
      "external": false,
      "loc": "net/core/dev.c:5119",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588575280,
      "name": "netif_receive_skb_list_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
void netif_receive_skb_list_internal(struct list_head * head)
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
