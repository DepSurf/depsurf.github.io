# Function: <code>napi_by_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct napi_struct * napi_by_id(unsigned int napi_id)
```

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586265296,
      "name": "napi_by_id",
      "external": true,
      "loc": "net/core/dev.c:4672",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586265296,
      "name": "napi_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586722690,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:4953",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:sk_busy_loop"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586887609,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:5035",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:sk_busy_loop"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587012109,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:5254",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587510061,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:5395",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587829853,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:5525",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587963870,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6078",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588277737,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6088",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588483416,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6014",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589352252,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6404",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_hash_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589358120,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6506",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589256457,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6627",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589982068,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6613",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591501157,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6099",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add_weight",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593277789,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6088",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add_weight",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593733629,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6065",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add_weight",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct napi_struct * napi_by_id(unsigned int napi_id)
```

```json
{
  "name": "napi_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594515841,
      "name": "napi_by_id",
      "external": true,
      "loc": "net/core/dev.c:6147",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add_weight",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
      ],
      "caller_func": [
        "net/core/netdev-genl.c:netdev_nl_napi_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594561616,
      "name": "napi_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502012244,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6014",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234747888,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6014",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295426320,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6014",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278301808,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6014",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588090200,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6014",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587803144,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6014",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588421976,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6014",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
  "name": "napi_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588544632,
      "name": "napi_by_id",
      "external": false,
      "loc": "net/core/dev.c:6014",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:dev_get_by_napi_id"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct napi_struct * napi_by_id(unsigned int napi_id)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct napi_struct * napi_by_id(unsigned int napi_id)
```
</details>
</li>
</ul>
