# Function: <code>hygon_get_topology</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579141269,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:63",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579152949,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:65",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579155509,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:65",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
void hygon_get_topology(struct cpuinfo_x86 * c)
```

```json
{
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579173328,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:65",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173328,
      "name": "hygon_get_topology",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void hygon_get_topology(struct cpuinfo_x86 * c)
```

```json
{
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579170128,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:63",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170128,
      "name": "hygon_get_topology",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579177148,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:63",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579211046,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:63",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579261928,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:63",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579324200,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:63",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579332760,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:63",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579362813,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:64",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579155877,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:65",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579086753,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:65",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579155429,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:65",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
  "name": "hygon_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579160565,
      "name": "hygon_get_topology",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hygon.c:65",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
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
void hygon_get_topology(struct cpuinfo_x86 * c)
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
void hygon_get_topology(struct cpuinfo_x86 * c)
```
</details>
</li>
</ul>
