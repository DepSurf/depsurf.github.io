# Function: <code>disable_err_thresholding</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```

```json
{
  "name": "disable_err_thresholding",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579177408,
      "name": "disable_err_thresholding",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:586",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177408,
      "name": "disable_err_thresholding",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```

```json
{
  "name": "disable_err_thresholding",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179808,
      "name": "disable_err_thresholding",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:588",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179808,
      "name": "disable_err_thresholding",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
  "name": "disable_err_thresholding",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579199805,
      "name": "disable_err_thresholding",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:602",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "disable_err_thresholding",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579195469,
      "name": "disable_err_thresholding",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:602",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "disable_err_thresholding",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579201613,
      "name": "disable_err_thresholding",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:602",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "disable_err_thresholding",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579237901,
      "name": "disable_err_thresholding",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:615",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "disable_err_thresholding",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579289207,
      "name": "disable_err_thresholding",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:638",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "disable_err_thresholding",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579354839,
      "name": "disable_err_thresholding",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:638",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "disable_err_thresholding",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579363879,
      "name": "disable_err_thresholding",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:640",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "disable_err_thresholding",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579393847,
      "name": "disable_err_thresholding",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:632",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```

```json
{
  "name": "disable_err_thresholding",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180064,
      "name": "disable_err_thresholding",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:588",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180064,
      "name": "disable_err_thresholding",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```

```json
{
  "name": "disable_err_thresholding",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112640,
      "name": "disable_err_thresholding",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:588",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112640,
      "name": "disable_err_thresholding",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```

```json
{
  "name": "disable_err_thresholding",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179728,
      "name": "disable_err_thresholding",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:588",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179728,
      "name": "disable_err_thresholding",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```

```json
{
  "name": "disable_err_thresholding",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579184912,
      "name": "disable_err_thresholding",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:588",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184912,
      "name": "disable_err_thresholding",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
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
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 * c, unsigned int bank)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
