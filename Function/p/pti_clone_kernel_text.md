# Function: <code>pti_clone_kernel_text</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pti_clone_kernel_text()
```

```json
{
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383440,
      "name": "pti_clone_kernel_text",
      "external": true,
      "loc": "arch/x86/mm/pti.c:464",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:mark_rodata_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383440,
      "name": "pti_clone_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579411085,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:572",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579426750,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:566",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579430013,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:568",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
void pti_clone_kernel_text()
```

```json
{
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579455424,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:561",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455424,
      "name": "pti_clone_kernel_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void pti_clone_kernel_text()
```

```json
{
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452288,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:554",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452288,
      "name": "pti_clone_kernel_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579454820,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:553",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579520228,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:553",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579604438,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:553",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579717958,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:553",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579731510,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:553",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579766454,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:553",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579425853,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:568",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579354973,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:568",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579425773,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:568",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
  "name": "pti_clone_kernel_text",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434957,
      "name": "pti_clone_kernel_text",
      "external": false,
      "loc": "arch/x86/mm/pti.c:568",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_finalize"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void pti_clone_kernel_text()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void pti_clone_kernel_text()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pti_clone_kernel_text()
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
void pti_clone_kernel_text()
```
</details>
</li>
</ul>
