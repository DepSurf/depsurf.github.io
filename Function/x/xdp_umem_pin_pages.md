# Function: <code>xdp_umem_pin_pages</code>

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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589122465,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:201",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589356393,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:252",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589813379,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:242",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590038518,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:282",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
int xdp_umem_pin_pages(struct xdp_umem * umem, long unsigned int address)
```

```json
{
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591068336,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:246",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068336,
      "name": "xdp_umem_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int xdp_umem_pin_pages(struct xdp_umem * umem, long unsigned int address)
```

```json
{
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591133168,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:96",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591133168,
      "name": "xdp_umem_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int xdp_umem_pin_pages(struct xdp_umem * umem, long unsigned int address)
```

```json
{
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591064000,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:96",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591064000,
      "name": "xdp_umem_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591907148,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:96",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
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
int xdp_umem_pin_pages(struct xdp_umem * umem, long unsigned int address)
```

```json
{
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593627440,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:96",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593627440,
      "name": "xdp_umem_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595557656,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:94",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596065987,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:94",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596933825,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:94",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503792752,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:282",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236411944,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:282",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297635216,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:282",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279697644,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:282",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589642118,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:282",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589366646,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:282",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590084150,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:282",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590134358,
      "name": "xdp_umem_pin_pages",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:282",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
int xdp_umem_pin_pages(struct xdp_umem * umem, long unsigned int address)
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
int xdp_umem_pin_pages(struct xdp_umem * umem, long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int xdp_umem_pin_pages(struct xdp_umem * umem, long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int xdp_umem_pin_pages(struct xdp_umem * umem, long unsigned int address)
```
</details>
</li>
</ul>
