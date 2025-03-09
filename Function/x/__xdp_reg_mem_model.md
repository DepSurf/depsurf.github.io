# Function: <code>__xdp_reg_mem_model</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct xdp_mem_allocator * __xdp_reg_mem_model(struct xdp_mem_info * mem, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "__xdp_reg_mem_model",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xdp_reg_mem_model",
      "external": false,
      "loc": "net/core/xdp.c:270",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591758064,
      "name": "__xdp_reg_mem_model",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
    },
    {
      "addr": 18446744071594590482,
      "name": "__xdp_reg_mem_model.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct xdp_mem_allocator * __xdp_reg_mem_model(struct xdp_mem_info * mem, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "__xdp_reg_mem_model",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xdp_reg_mem_model",
      "external": false,
      "loc": "net/core/xdp.c:270",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:xdp_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593549664,
      "name": "__xdp_reg_mem_model",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
    },
    {
      "addr": 18446744071596328959,
      "name": "__xdp_reg_mem_model.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct xdp_mem_allocator * __xdp_reg_mem_model(struct xdp_mem_info * mem, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "__xdp_reg_mem_model",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xdp_reg_mem_model",
      "external": false,
      "loc": "net/core/xdp.c:272",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:xdp_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594018464,
      "name": "__xdp_reg_mem_model",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071596859028,
      "name": "__xdp_reg_mem_model.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct xdp_mem_allocator * __xdp_reg_mem_model(struct xdp_mem_info * mem, enum xdp_mem_type type, void * allocator)
```

```json
{
  "name": "__xdp_reg_mem_model",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xdp_reg_mem_model",
      "external": false,
      "loc": "net/core/xdp.c:272",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:xdp_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594804496,
      "name": "__xdp_reg_mem_model",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    },
    {
      "addr": 18446744071597784096,
      "name": "__xdp_reg_mem_model.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
struct xdp_mem_allocator * __xdp_reg_mem_model(struct xdp_mem_info * mem, enum xdp_mem_type type, void * allocator)
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
