# Function: <code>pti_setup_vsyscall</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602722754,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:250",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602895039,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:274",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604692601,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:284",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604792405,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:278",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604818255,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:278",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
void pti_setup_vsyscall()
```

```json
{
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609156040,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:278",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609156040,
      "name": "pti_setup_vsyscall",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 143
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
void pti_setup_vsyscall()
```

```json
{
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612226535,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:277",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612226535,
      "name": "pti_setup_vsyscall",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 143
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614367841,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:277",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615299391,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:277",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617079381,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:277",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627733145,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:277",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619492393,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:277",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621789209,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:277",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604732135,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:278",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604699860,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:278",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604809702,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:278",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
  "name": "pti_setup_vsyscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604822383,
      "name": "pti_setup_vsyscall",
      "external": false,
      "loc": "arch/x86/mm/pti.c:278",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
void pti_setup_vsyscall()
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
void pti_setup_vsyscall()
```
</details>
</li>
</ul>
