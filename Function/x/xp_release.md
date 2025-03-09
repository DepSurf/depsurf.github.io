# Function: <code>xp_release</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xp_release(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591064691,
      "name": "xp_release",
      "external": true,
      "loc": "net/xdp/xsk.c:102",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067728,
      "name": "xp_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void xp_release(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591127995,
      "name": "xp_release",
      "external": true,
      "loc": "net/xdp/xsk.c:137",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591132464,
      "name": "xp_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void xp_release(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591058287,
      "name": "xp_release",
      "external": true,
      "loc": "net/xdp/xsk.c:137",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591063216,
      "name": "xp_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void xp_release(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591900641,
      "name": "xp_release",
      "external": true,
      "loc": "net/xdp/xsk.c:137",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591906096,
      "name": "xp_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
  "name": "xp_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593619887,
      "name": "xp_release",
      "external": false,
      "loc": "include/net/xsk_buff_pool.h:213",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_rcv_zc"
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
  "name": "xp_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595548671,
      "name": "xp_release",
      "external": false,
      "loc": "include/net/xsk_buff_pool.h:213",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_rcv_zc"
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
  "name": "xp_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596056927,
      "name": "xp_release",
      "external": false,
      "loc": "include/net/xsk_buff_pool.h:213",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_rcv_zc"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xp_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596922408,
      "name": "xp_release",
      "external": false,
      "loc": "include/net/xsk_buff_pool.h:225",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_rcv_zc"
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
void xp_release(struct xdp_buff_xsk * xskb)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void xp_release(struct xdp_buff_xsk * xskb)
```
</details>
</li>
</ul>
