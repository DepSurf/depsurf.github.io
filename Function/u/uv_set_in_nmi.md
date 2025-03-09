# Function: <code>uv_set_in_nmi</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```

```json
{
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472848,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:454",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472848,
      "name": "uv_set_in_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579495072,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:454",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495072,
      "name": "uv_set_in_nmi.isra.0",
      "section": ".text",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579477504,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:496",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477504,
      "name": "uv_set_in_nmi.isra.0",
      "section": ".text",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479488,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:499",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479488,
      "name": "uv_set_in_nmi.isra.0",
      "section": ".text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545760,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:499",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545760,
      "name": "uv_set_in_nmi.isra.0",
      "section": ".text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579634944,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:500",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634944,
      "name": "uv_set_in_nmi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749648,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:500",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749648,
      "name": "uv_set_in_nmi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579796208,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:500",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796208,
      "name": "uv_set_in_nmi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579829904,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:499",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829904,
      "name": "uv_set_in_nmi.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```

```json
{
  "name": "uv_set_in_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579478176,
      "name": "uv_set_in_nmi",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:454",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478176,
      "name": "uv_set_in_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
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
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s * hub_nmi)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
