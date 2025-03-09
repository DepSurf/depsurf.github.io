# Function: <code>generic_xdp_tx</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587039971,
      "name": "generic_xdp_tx",
      "external": false,
      "loc": "net/core/dev.c:4437",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_internal"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587537984,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:3997",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:do_xdp_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587537984,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587841888,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4116",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587841888,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587975536,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4425",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975536,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588289376,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4439",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289376,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588494752,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4341",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588494752,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589365696,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4704",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589365696,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589371264,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4733",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371264,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589267216,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4841",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589267216,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589994240,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4832",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589994240,
      "name": "generic_xdp_tx",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591535248,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4872",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/dev.c:do_xdp_generic",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591535248,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593308976,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4859",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/dev.c:do_xdp_generic",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593308976,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593770688,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4834",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/dev.c:do_xdp_generic",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593770688,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594550272,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4982",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/dev.c:do_xdp_generic",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594550272,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502026312,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4341",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502026312,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234778164,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4341",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234778164,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295469024,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4341",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295469024,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278316522,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4341",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278316522,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588101536,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4341",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101536,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587814448,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4341",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814448,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588433312,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4341",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433312,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "generic_xdp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588569680,
      "name": "generic_xdp_tx",
      "external": true,
      "loc": "net/core/dev.c:4341",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588569680,
      "name": "generic_xdp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void generic_xdp_tx(struct sk_buff * skb, struct bpf_prog * xdp_prog)
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
