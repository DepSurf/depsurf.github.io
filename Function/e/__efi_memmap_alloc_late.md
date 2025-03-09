# Function: <code>__efi_memmap_alloc_late</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595762932,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:20",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596692008,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:20",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603022065,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603194800,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605005148,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```

```json
{
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605117750,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605117750,
      "name": "__efi_memmap_alloc_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```

```json
{
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605157199,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605157199,
      "name": "__efi_memmap_alloc_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609426542,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612500348,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614642537,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615600495,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617410201,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627740497,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "arch/x86/platform/efi/memmap.c:22",
      "file": "arch/x86/platform/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619499937,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "arch/x86/platform/efi/memmap.c:22",
      "file": "arch/x86/platform/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621796769,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "arch/x86/platform/efi/memmap.c:22",
      "file": "arch/x86/platform/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511285108,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243936528,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```

```json
{
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605047637,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605047637,
      "name": "__efi_memmap_alloc_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```

```json
{
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605012977,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605012977,
      "name": "__efi_memmap_alloc_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```

```json
{
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605134212,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605134212,
      "name": "__efi_memmap_alloc_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```

```json
{
  "name": "__efi_memmap_alloc_late",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605161393,
      "name": "__efi_memmap_alloc_late",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:21",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605161393,
      "name": "__efi_memmap_alloc_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
phys_addr_t __efi_memmap_alloc_late(long unsigned int size)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
