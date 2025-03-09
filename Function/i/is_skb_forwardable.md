# Function: <code>is_skb_forwardable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(struct net_device * dev, struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586277856,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1726",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277856,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586703824,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1746",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703824,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586890432,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1767",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586890432,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587014608,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1801",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587014608,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587513040,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1816",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587513040,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587815488,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1860",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587815488,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587950336,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1894",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587950336,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588260112,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1904",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588260112,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588465232,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588465232,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589339883,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:2182",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/dev.c:__dev_forward_skb"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589333168,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589341931,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:2207",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/dev.c:__dev_forward_skb"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589334208,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589229712,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:2276",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589229712,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589953152,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:2151",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589953152,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591491696,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:2128",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591491696,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593260160,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:2113",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593260160,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593718064,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:2139",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593718064,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594499504,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:2143",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594499504,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501989480,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501989480,
      "name": "is_skb_forwardable",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234748204,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234748204,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295426880,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295426880,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278288350,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278288350,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588072016,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588072016,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587785440,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785440,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588403792,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588403792,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool is_skb_forwardable(const struct net_device * dev, const struct sk_buff * skb)
```

```json
{
  "name": "is_skb_forwardable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588540608,
      "name": "is_skb_forwardable",
      "external": true,
      "loc": "net/core/dev.c:1822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588540608,
      "name": "is_skb_forwardable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct net_device * dev</code> ➡️ <code>const struct net_device * dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct sk_buff * skb</code> ➡️ <code>const struct sk_buff * skb</code>
</li>
</ul>
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
