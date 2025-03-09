# Function: <code>skb_segment_list</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment_list(struct sk_buff * skb, netdev_features_t features, unsigned int offset)
```

```json
{
  "name": "skb_segment_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment_list",
      "external": true,
      "loc": "net/core/skbuff.c:3640",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284509,
      "name": "skb_segment_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071589271248,
      "name": "skb_segment_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment_list(struct sk_buff * skb, netdev_features_t features, unsigned int offset)
```

```json
{
  "name": "skb_segment_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment_list",
      "external": true,
      "loc": "net/core/skbuff.c:3690",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591627310,
      "name": "skb_segment_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071589272480,
      "name": "skb_segment_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment_list(struct sk_buff * skb, netdev_features_t features, unsigned int offset)
```

```json
{
  "name": "skb_segment_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment_list",
      "external": true,
      "loc": "net/core/skbuff.c:3775",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591570691,
      "name": "skb_segment_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071589165632,
      "name": "skb_segment_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment_list(struct sk_buff * skb, netdev_features_t features, unsigned int offset)
```

```json
{
  "name": "skb_segment_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment_list",
      "external": true,
      "loc": "net/core/skbuff.c:3835",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694666,
      "name": "skb_segment_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071589886096,
      "name": "skb_segment_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * skb_segment_list(struct sk_buff * skb, netdev_features_t features, unsigned int offset)
```

```json
{
  "name": "skb_segment_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_segment_list",
      "external": true,
      "loc": "net/core/skbuff.c:3885",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594580143,
      "name": "skb_segment_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071591414832,
      "name": "skb_segment_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1060
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
struct sk_buff * skb_segment_list(struct sk_buff * skb, netdev_features_t features, unsigned int offset)
```

```json
{
  "name": "skb_segment_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593182816,
      "name": "skb_segment_list",
      "external": true,
      "loc": "net/core/skbuff.c:4087",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593182816,
      "name": "skb_segment_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1124
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
struct sk_buff * skb_segment_list(struct sk_buff * skb, netdev_features_t features, unsigned int offset)
```

```json
{
  "name": "skb_segment_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593641040,
      "name": "skb_segment_list",
      "external": true,
      "loc": "net/core/skbuff.c:4256",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593641040,
      "name": "skb_segment_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1196
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
struct sk_buff * skb_segment_list(struct sk_buff * skb, netdev_features_t features, unsigned int offset)
```

```json
{
  "name": "skb_segment_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594416976,
      "name": "skb_segment_list",
      "external": true,
      "loc": "net/core/skbuff.c:4378",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:__udp_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594416976,
      "name": "skb_segment_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1196
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct sk_buff * skb_segment_list(struct sk_buff * skb, netdev_features_t features, unsigned int offset)
```
</details>
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
