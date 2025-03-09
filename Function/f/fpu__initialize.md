# Function: <code>fpu__initialize</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fpu__initialize(struct fpu * fpu)
```

```json
{
  "name": "fpu__initialize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579077904,
      "name": "fpu__initialize",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:227",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077904,
      "name": "fpu__initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fpu__initialize(struct fpu * fpu)
```

```json
{
  "name": "fpu__initialize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579083424,
      "name": "fpu__initialize",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:228",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083424,
      "name": "fpu__initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fpu__initialize(struct fpu * fpu)
```

```json
{
  "name": "fpu__initialize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579088832,
      "name": "fpu__initialize",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:226",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088832,
      "name": "fpu__initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fpu__initialize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579100159,
      "name": "fpu__initialize",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:214",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear"
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
  "name": "fpu__initialize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579102143,
      "name": "fpu__initialize",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:214",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fpu__initialize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579102527,
      "name": "fpu__initialize",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:214",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear"
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
  "name": "fpu__initialize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579034943,
      "name": "fpu__initialize",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:214",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear"
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
  "name": "fpu__initialize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579102079,
      "name": "fpu__initialize",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:214",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear"
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
  "name": "fpu__initialize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579106847,
      "name": "fpu__initialize",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:214",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void fpu__initialize(struct fpu * fpu)
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
void fpu__initialize(struct fpu * fpu)
```
</details>
</li>
</ul>
