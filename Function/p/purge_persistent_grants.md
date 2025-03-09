# Function: <code>purge_persistent_grants</code>

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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585989560,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2652",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586234008,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2652",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586382232,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2652",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
void purge_persistent_grants(struct blkfront_info * info)
```

```json
{
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587151680,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2658",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587151680,
      "name": "purge_persistent_grants",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void purge_persistent_grants(struct blkfront_info * info)
```

```json
{
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587235952,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2653",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235952,
      "name": "purge_persistent_grants",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587130651,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2653",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587705003,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2526",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589049034,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2521",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590578170,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2523",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590919402,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2524",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591263258,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2524",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499238796,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2652",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586147544,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2798",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586330200,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2652",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
  "name": "purge_persistent_grants",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586441928,
      "name": "purge_persistent_grants",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2652",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work"
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
void purge_persistent_grants(struct blkfront_info * info)
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
void purge_persistent_grants(struct blkfront_info * info)
```
</details>
</li>
</ul>
