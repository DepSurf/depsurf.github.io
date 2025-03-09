# Function: <code>tun_xdp_act</code>

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
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586580736,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1630",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586580736,
      "name": "tun_xdp_act.isra.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586832624,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586832624,
      "name": "tun_xdp_act.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978688,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978688,
      "name": "tun_xdp_act.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587809968,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1588",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587809968,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867936,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1519",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867936,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587747200,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1530",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747200,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588342784,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1586",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588342784,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589733232,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1614",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589733232,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591349008,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1617",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591349008,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591710736,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591710736,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592452656,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1626",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592452656,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499974112,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499974112,
      "name": "tun_xdp_act.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232509904,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232509904,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293298320,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293298320,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277050816,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277050816,
      "name": "tun_xdp_act",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586735696,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735696,
      "name": "tun_xdp_act.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586602912,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602912,
      "name": "tun_xdp_act.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586933248,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586933248,
      "name": "tun_xdp_act.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_xdp_act",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587040272,
      "name": "tun_xdp_act",
      "external": false,
      "loc": "drivers/net/tun.c:1623",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040272,
      "name": "tun_xdp_act.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int tun_xdp_act(struct tun_struct * tun, struct bpf_prog * xdp_prog, struct xdp_buff * xdp, u32 act)
```
</details>
</li>
</ul>
