# Function: <code>apply_microcode_early_amd</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool apply_microcode_early_amd(void * ucode, size_t size, bool save_patch, struct container * ret_cont)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579177568,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:222",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177568,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579175392,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:200",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579175392,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579190656,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:200",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190656,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202368,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:200",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202368,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579193008,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:421",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193008,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205856,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:419",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205856,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208112,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:419",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208112,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579229840,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:419",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229840,
      "name": "apply_microcode_early_amd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223280,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:418",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223280,
      "name": "apply_microcode_early_amd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579225840,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:418",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225840,
      "name": "apply_microcode_early_amd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579264464,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:418",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264464,
      "name": "apply_microcode_early_amd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579315904,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:418",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315904,
      "name": "apply_microcode_early_amd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579381488,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:420",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381488,
      "name": "apply_microcode_early_amd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206960,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:419",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206960,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141808,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:419",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141808,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208032,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:419",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208032,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```

```json
{
  "name": "apply_microcode_early_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213312,
      "name": "apply_microcode_early_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:419",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213312,
      "name": "apply_microcode_early_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool apply_microcode_early_amd(void * ucode, size_t size, bool save_patch, struct container * ret_cont)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 cpuid_1_eax</code>
</li>
<li>
<b>Param removed. </b>
<code>struct container * ret_cont</code>
</li>
<li>
<b>Param reordered. </b>
<code>ucode, size, save_patch, ret_cont</code> ➡️ <code>cpuid_1_eax, ucode, size, save_patch</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
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
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool apply_microcode_early_amd(u32 cpuid_1_eax, void * ucode, size_t size, bool save_patch)
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
