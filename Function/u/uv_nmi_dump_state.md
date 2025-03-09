# Function: <code>uv_nmi_dump_state</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579474609,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:751",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
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
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579496837,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:751",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
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
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579478964,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:793",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
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
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579480996,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:796",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
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
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579546727,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:796",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
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
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579635878,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:797",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void uv_nmi_dump_state(int cpu, struct pt_regs * regs, int master)
```

```json
{
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751872,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:797",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751872,
      "name": "uv_nmi_dump_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void uv_nmi_dump_state(int cpu, struct pt_regs * regs, int master)
```

```json
{
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798432,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:797",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798432,
      "name": "uv_nmi_dump_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void uv_nmi_dump_state(int cpu, struct pt_regs * regs, int master)
```

```json
{
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831056,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:796",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831056,
      "name": "uv_nmi_dump_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_nmi_dump_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579479935,
      "name": "uv_nmi_dump_state",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:751",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void uv_nmi_dump_state(int cpu, struct pt_regs * regs, int master)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
