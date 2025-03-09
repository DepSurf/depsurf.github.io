# Function: <code>ip_list_rcv</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588371088,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:585",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588371088,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588773920,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588773920,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588997520,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588997520,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589955616,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:612",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589955616,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589996464,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:612",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589996464,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589910672,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:613",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589910672,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590677088,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:613",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590677088,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592304240,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:637",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592304240,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594140464,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:642",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594140464,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594527584,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:642",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594527584,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595330304,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:643",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595330304,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502603528,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502603528,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235309088,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235309088,
      "name": "ip_list_rcv",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296195152,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296195152,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278754392,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278754392,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588603904,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588603904,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588315888,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315888,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589040080,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589040080,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ip_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589079232,
      "name": "ip_list_rcv",
      "external": true,
      "loc": "net/ipv4/ip_input.c:584",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589079232,
      "name": "ip_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void ip_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```
</details>
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
