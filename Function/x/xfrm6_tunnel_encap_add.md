# Function: <code>xfrm6_tunnel_encap_add</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589290519,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589514903,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int xfrm6_tunnel_encap_add(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590505872,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:242",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590505872,
      "name": "xfrm6_tunnel_encap_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
int xfrm6_tunnel_encap_add(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590565440,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:242",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590565440,
      "name": "xfrm6_tunnel_encap_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590490880,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:242",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590490880,
      "name": "xfrm6_tunnel_encap_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591295856,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:319",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591295856,
      "name": "xfrm6_tunnel_encap_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592962640,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:320",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592962640,
      "name": "xfrm6_tunnel_encap_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594848896,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:318",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594848896,
      "name": "xfrm6_tunnel_encap_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595240064,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:319",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595240064,
      "name": "xfrm6_tunnel_encap_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596080512,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:319",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596080512,
      "name": "xfrm6_tunnel_encap_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503179996,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235854380,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296907808,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279221234,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589119271,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588844311,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589556135,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_tunnel_encap_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589603639,
      "name": "xfrm6_tunnel_encap_add",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:236",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int xfrm6_tunnel_encap_add(struct xfrm_state * x, struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int xfrm6_tunnel_encap_add(struct xfrm_state * x, struct sk_buff * skb)
```
</details>
</li>
</ul>
