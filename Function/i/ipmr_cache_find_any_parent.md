# Function: <code>ipmr_cache_find_any_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_cache_find_any_parent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586868941,
      "name": "ipmr_cache_find_any_parent",
      "external": false,
      "loc": "net/ipv4/ipmr.c:836",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ip_mr_forward"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_cache_find_any_parent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587328495,
      "name": "ipmr_cache_find_any_parent",
      "external": false,
      "loc": "net/ipv4/ipmr.c:848",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ipmr_cache_find_any"
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
  "name": "ipmr_cache_find_any_parent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587531331,
      "name": "ipmr_cache_find_any_parent",
      "external": false,
      "loc": "net/ipv4/ipmr.c:853",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ipmr_cache_find_any"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache * ipmr_cache_find_any_parent(struct mr_table * mrt, int vifi)
```

```json
{
  "name": "ipmr_cache_find_any_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587673984,
      "name": "ipmr_cache_find_any_parent",
      "external": false,
      "loc": "net/ipv4/ipmr.c:877",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ipmr_cache_find_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587673984,
      "name": "ipmr_cache_find_any_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
struct mfc_cache * ipmr_cache_find_any_parent(struct mr_table * mrt, int vifi)
```

```json
{
  "name": "ipmr_cache_find_any_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588200400,
      "name": "ipmr_cache_find_any_parent",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1002",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_cache_find_any",
        "net/ipv4/ipmr.c:ipmr_cache_find_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588200400,
      "name": "ipmr_cache_find_any_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    }
  ]
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct mfc_cache * ipmr_cache_find_any_parent(struct mr_table * mrt, int vifi)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct mfc_cache * ipmr_cache_find_any_parent(struct mr_table * mrt, int vifi)
```
</details>
</li>
</ul>
