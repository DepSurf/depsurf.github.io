# Function: <code>balloon_retrieve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * balloon_retrieve(bool require_lowmem)
```

```json
{
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851424,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:188",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:alloc_xenballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851424,
      "name": "balloon_retrieve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584182304,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:187",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584182304,
      "name": "balloon_retrieve.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584365238,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:186",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584446852,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:187",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584856773,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:187",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585087655,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:187",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585197911,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:181",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585410361,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:178",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585551074,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:175",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586269930,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:174",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:increase_reservation"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586387786,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:173",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:increase_reservation"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586271577,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:173",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586783593,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:180",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_thread"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588062188,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:182",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:xen_alloc_ballooned_pages",
        "drivers/xen/balloon.c:balloon_thread"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589443884,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:182",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:xen_alloc_ballooned_pages",
        "drivers/xen/balloon.c:balloon_thread"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589743308,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:164",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:xen_alloc_ballooned_pages",
        "drivers/xen/balloon.c:balloon_thread"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590081324,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:163",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:xen_alloc_ballooned_pages",
        "drivers/xen/balloon.c:balloon_thread"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498211504,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:175",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498211504,
      "name": "balloon_retrieve.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585312515,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:175",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585501474,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:175",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
  "name": "balloon_retrieve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585609506,
      "name": "balloon_retrieve",
      "external": false,
      "loc": "drivers/xen/balloon.c:175",
      "file": "drivers/xen/balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process"
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
struct page * balloon_retrieve(bool require_lowmem)
```
</details>
</li>
</ul>
