# Function: <code>xen_setup_gdt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_setup_gdt(int cpu)
```

```json
{
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587332112,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten.c:1413",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_pvh_secondary_vcpu_init",
        "arch/x86/xen/enlighten.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587332112,
      "name": "xen_setup_gdt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void xen_setup_gdt(int cpu)
```

```json
{
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587830512,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten.c:1433",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_pvh_secondary_vcpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587830512,
      "name": "xen_setup_gdt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void xen_setup_gdt(int cpu)
```

```json
{
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588045824,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten.c:1421",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_pvh_secondary_vcpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588045824,
      "name": "xen_setup_gdt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596301334,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1212",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602619136,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1202",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602787396,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1178",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581576,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1174",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604676872,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1175",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604689351,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1169",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609040291,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1225",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612103659,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1188",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614243156,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1202",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615163328,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1176",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616929745,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1165",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627534090,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1208",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619280450,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1263",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621573010,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1289",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604615632,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1169",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604693447,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1169",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_setup_gdt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604693403,
      "name": "xen_setup_gdt",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:1169",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void xen_setup_gdt(int cpu)
```
</details>
</li>
</ul>
