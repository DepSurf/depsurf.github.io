# Function: <code>kernel_fpu_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kernel_fpu_disable()
```

```json
{
  "name": "kernel_fpu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081168,
      "name": "kernel_fpu_disable",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:39",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081168,
      "name": "kernel_fpu_disable",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void kernel_fpu_disable()
```

```json
{
  "name": "kernel_fpu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077744,
      "name": "kernel_fpu_disable",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:43",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077744,
      "name": "kernel_fpu_disable",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kernel_fpu_disable()
```

```json
{
  "name": "kernel_fpu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076176,
      "name": "kernel_fpu_disable",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:45",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076176,
      "name": "kernel_fpu_disable",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kernel_fpu_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579069223,
      "name": "kernel_fpu_disable",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:44",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void kernel_fpu_disable()
```

```json
{
  "name": "kernel_fpu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077536,
      "name": "kernel_fpu_disable",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:44",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077536,
      "name": "kernel_fpu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void kernel_fpu_disable()
```

```json
{
  "name": "kernel_fpu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082304,
      "name": "kernel_fpu_disable",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:45",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082304,
      "name": "kernel_fpu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void kernel_fpu_disable()
```

```json
{
  "name": "kernel_fpu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087712,
      "name": "kernel_fpu_disable",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:45",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087712,
      "name": "kernel_fpu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
void kernel_fpu_disable()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void kernel_fpu_disable()
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void kernel_fpu_disable()
```
</details>
</li>
</ul>
