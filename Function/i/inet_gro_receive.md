# Function: <code>inet_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * * inet_gro_receive(struct sk_buff * * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586790304,
      "name": "inet_gro_receive",
      "external": false,
      "loc": "net/ipv4/af_inet.c:1289",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790304,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
struct sk_buff * * inet_gro_receive(struct sk_buff * * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587238608,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1285",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587238608,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
struct sk_buff * * inet_gro_receive(struct sk_buff * * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587438816,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1297",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587438816,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
struct sk_buff * * inet_gro_receive(struct sk_buff * * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587580784,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1315",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587580784,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
struct sk_buff * * inet_gro_receive(struct sk_buff * * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588104720,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1319",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588104720,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 695
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
struct sk_buff * * inet_gro_receive(struct sk_buff * * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588458320,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1388",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458320,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588645840,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1392",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588645840,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589058208,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589058208,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589282480,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282480,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590259568,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1439",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590259568,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590312496,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1433",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590312496,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590228352,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1436",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590228352,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591011632,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1441",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591011632,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592659152,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1436",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gro.c:dev_gro_receive",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592659152,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594525072,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1456",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gro.c:dev_gro_receive",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594525072,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594916480,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1455",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gro.c:dev_gro_receive",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594916480,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595728448,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1475",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gro.c:dev_gro_receive",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595728448,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502911504,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502911504,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235604904,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235604904,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296582208,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296582208,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279007308,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279007308,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588888656,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588888656,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588600592,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588600592,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589325040,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325040,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
struct sk_buff * inet_gro_receive(struct list_head * head, struct sk_buff * skb)
```

```json
{
  "name": "inet_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589373568,
      "name": "inet_gro_receive",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1407",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_gro_receive",
        "net/ipv4/af_inet.c:ipip_gro_receive",
        "net/ipv6/ip6_offload.c:ip4ip6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589373568,
      "name": "inet_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sk_buff * * head</code> ➡️ <code>struct list_head * head</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct sk_buff * *</code> ➡️ <code>struct sk_buff *</code>
</li>
</ul>
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
