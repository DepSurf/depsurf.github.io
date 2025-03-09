# Function: <code>free_info</code>

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
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585995787,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1766",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
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
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586250088,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1766",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
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
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586398290,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1766",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_info(struct blkfront_info * info)
```

```json
{
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587167417,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1776",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587148160,
      "name": "free_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void free_info(struct blkfront_info * info)
```

```json
{
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587251640,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1777",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587232448,
      "name": "free_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void free_info(struct blkfront_info * info)
```

```json
{
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587138856,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1777",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587121136,
      "name": "free_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499236756,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1766",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586160870,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1791",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586346258,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1766",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
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
  "name": "free_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586457930,
      "name": "free_info",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1766",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:talk_to_blkback"
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
void free_info(struct blkfront_info * info)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void free_info(struct blkfront_info * info)
```
</details>
</li>
</ul>
