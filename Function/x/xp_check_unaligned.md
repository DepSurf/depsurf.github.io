# Function: <code>xp_check_unaligned</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xp_check_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591073379,
      "name": "xp_check_unaligned",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:163",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
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
  "name": "xp_check_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591137951,
      "name": "xp_check_unaligned",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:432",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
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
  "name": "xp_check_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591068332,
      "name": "xp_check_unaligned",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:426",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
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
  "name": "xp_check_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591911474,
      "name": "xp_check_unaligned",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:426",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool xp_check_unaligned(struct xsk_buff_pool * pool, u64 * addr)
```

```json
{
  "name": "xp_check_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593631184,
      "name": "xp_check_unaligned",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:454",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq",
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593631184,
      "name": "xp_check_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
bool xp_check_unaligned(struct xsk_buff_pool * pool, u64 * addr)
```

```json
{
  "name": "xp_check_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595561424,
      "name": "xp_check_unaligned",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:459",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq",
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595561424,
      "name": "xp_check_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
bool xp_check_unaligned(struct xsk_buff_pool * pool, u64 * addr)
```

```json
{
  "name": "xp_check_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596069872,
      "name": "xp_check_unaligned",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:463",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq",
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596069872,
      "name": "xp_check_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
bool xp_check_unaligned(struct xsk_buff_pool * pool, u64 * addr)
```

```json
{
  "name": "xp_check_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596937872,
      "name": "xp_check_unaligned",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:487",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq",
        "net/xdp/xsk_buff_pool.c:__xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596937872,
      "name": "xp_check_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool xp_check_unaligned(struct xsk_buff_pool * pool, u64 * addr)
```
</details>
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
