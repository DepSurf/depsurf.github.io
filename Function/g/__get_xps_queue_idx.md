# Function: <code>__get_xps_queue_idx</code>

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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587947440,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:__netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587947440,
      "name": "__get_xps_queue_idx",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588256992,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3636",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256992,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588462144,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3536",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462144,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589327888,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3894",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589327888,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589327200,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3925",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589327200,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589222704,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:4006",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222704,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589944800,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3971",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589944800,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591479216,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:4003",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591479216,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593248240,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3990",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593248240,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593709056,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593709056,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594488128,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:4100",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594488128,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501986584,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3536",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501986584,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234741740,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3536",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234741740,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295419680,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3536",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295419680,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278284814,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3536",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278284814,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588068928,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3536",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588068928,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587782016,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3536",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587782016,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588400704,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3536",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588400704,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
```

```json
{
  "name": "__get_xps_queue_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588537104,
      "name": "__get_xps_queue_idx",
      "external": false,
      "loc": "net/core/dev.c:3536",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588537104,
      "name": "__get_xps_queue_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __get_xps_queue_idx(struct net_device * dev, struct sk_buff * skb, struct xps_dev_maps * dev_maps, unsigned int tci)
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
