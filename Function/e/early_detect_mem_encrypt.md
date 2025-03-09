# Function: <code>early_detect_mem_encrypt</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579130712,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:575",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579137458,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:574",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579149086,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:578",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579151534,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:580",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
void early_detect_mem_encrypt(struct cpuinfo_x86 * c)
```

```json
{
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579168784,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:605",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168784,
      "name": "early_detect_mem_encrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void early_detect_mem_encrypt(struct cpuinfo_x86 * c)
```

```json
{
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579165568,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:578",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579165568,
      "name": "early_detect_mem_encrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579173810,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:578",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579207341,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:578",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579258534,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:549",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579320678,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:549",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579328534,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:621",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579357326,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:596",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579151902,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:580",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579083445,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:580",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579151454,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:580",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
  "name": "early_detect_mem_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579156590,
      "name": "early_detect_mem_encrypt",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:580",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
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
void early_detect_mem_encrypt(struct cpuinfo_x86 * c)
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
void early_detect_mem_encrypt(struct cpuinfo_x86 * c)
```
</details>
</li>
</ul>
