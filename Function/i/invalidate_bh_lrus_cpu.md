# Function: <code>invalidate_bh_lrus_cpu</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void invalidate_bh_lrus_cpu(int cpu)
```

```json
{
  "name": "invalidate_bh_lrus_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582457728,
      "name": "invalidate_bh_lrus_cpu",
      "external": true,
      "loc": "fs/buffer.c:1453",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_add_drain_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457728,
      "name": "invalidate_bh_lrus_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void invalidate_bh_lrus_cpu()
```

```json
{
  "name": "invalidate_bh_lrus_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582781360,
      "name": "invalidate_bh_lrus_cpu",
      "external": true,
      "loc": "fs/buffer.c:1432",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_add_drain_per_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582781360,
      "name": "invalidate_bh_lrus_cpu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void invalidate_bh_lrus_cpu()
```

```json
{
  "name": "invalidate_bh_lrus_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583333488,
      "name": "invalidate_bh_lrus_cpu",
      "external": true,
      "loc": "fs/buffer.c:1431",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_per_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583333488,
      "name": "invalidate_bh_lrus_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void invalidate_bh_lrus_cpu()
```

```json
{
  "name": "invalidate_bh_lrus_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918080,
      "name": "invalidate_bh_lrus_cpu",
      "external": true,
      "loc": "fs/buffer.c:1420",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_per_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918080,
      "name": "invalidate_bh_lrus_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void invalidate_bh_lrus_cpu()
```

```json
{
  "name": "invalidate_bh_lrus_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140784,
      "name": "invalidate_bh_lrus_cpu",
      "external": true,
      "loc": "fs/buffer.c:1532",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_per_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140784,
      "name": "invalidate_bh_lrus_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void invalidate_bh_lrus_cpu()
```

```json
{
  "name": "invalidate_bh_lrus_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584356848,
      "name": "invalidate_bh_lrus_cpu",
      "external": true,
      "loc": "fs/buffer.c:1527",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_per_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584356848,
      "name": "invalidate_bh_lrus_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void invalidate_bh_lrus_cpu(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
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
