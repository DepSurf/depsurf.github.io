# Function: <code>collect_cpu_info_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163648,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:350",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163648,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163552,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:359",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163552,
      "name": "collect_cpu_info_early",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579173968,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:371",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173968,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579173680,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:383",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173680,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188576,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:388",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188576,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579199920,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:391",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579199920,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579189312,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:391",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579189312,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202128,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:388",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202128,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579204384,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:388",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204384,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579225312,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:388",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225312,
      "name": "collect_cpu_info_early.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579219264,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:345",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219264,
      "name": "collect_cpu_info_early.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221744,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:345",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221744,
      "name": "collect_cpu_info_early.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579260272,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:345",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260272,
      "name": "collect_cpu_info_early.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203232,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:388",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203232,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138192,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:388",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138192,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579204304,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:388",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204304,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```

```json
{
  "name": "collect_cpu_info_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579209584,
      "name": "collect_cpu_info_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:388",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209584,
      "name": "collect_cpu_info_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
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
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info * uci)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info * uci)
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
