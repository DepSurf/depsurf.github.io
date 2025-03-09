# Function: <code>init_pvh_bootparams</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596308153,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pvh.c:34",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602626153,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pvh.c:28",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602794989,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pvh.c:34",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604594884,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604690555,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604702851,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
void init_pvh_bootparams(bool xen_guest)
```

```json
{
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609050603,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609050603,
      "name": "init_pvh_bootparams",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 296
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
void init_pvh_bootparams(bool xen_guest)
```

```json
{
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612113991,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612113991,
      "name": "init_pvh_bootparams",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 296
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614254031,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615174702,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616940135,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627547419,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619293739,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621586331,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604629139,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604597183,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604706947,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
  "name": "init_pvh_bootparams",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604706963,
      "name": "init_pvh_bootparams",
      "external": false,
      "loc": "arch/x86/platform/pvh/enlighten.c:45",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
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
void init_pvh_bootparams(bool xen_guest)
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
void init_pvh_bootparams(bool xen_guest)
```
</details>
</li>
</ul>
