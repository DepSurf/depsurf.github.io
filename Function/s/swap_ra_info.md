# Function: <code>swap_ra_info</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581238260,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:664",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581321668,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:626",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581432745,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:640",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581496985,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:640",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
void swap_ra_info(struct vm_fault * vmf, struct vma_swap_readahead * ra_info)
```

```json
{
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698176,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:658",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swap_vma_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698176,
      "name": "swap_ra_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581745152,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:750",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swap_vma_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745152,
      "name": "swap_ra_info.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581773296,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:719",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swap_vma_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773296,
      "name": "swap_ra_info.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055936,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:712",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swap_vma_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055936,
      "name": "swap_ra_info.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582492640,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:725",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swap_vma_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492640,
      "name": "swap_ra_info.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583007472,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:709",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:swap_vma_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007472,
      "name": "swap_ra_info.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583221299,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:719",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583456614,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:733",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492917268,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:640",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226708132,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:640",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286324264,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:640",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272839202,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:640",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581465698,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:599",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581407963,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:640",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581457033,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:640",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
  "name": "swap_ra_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581521465,
      "name": "swap_ra_info",
      "external": false,
      "loc": "mm/swap_state.c:640",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
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
void swap_ra_info(struct vm_fault * vmf, struct vma_swap_readahead * ra_info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void swap_ra_info(struct vm_fault * vmf, struct vma_swap_readahead * ra_info)
```
</details>
</li>
</ul>
