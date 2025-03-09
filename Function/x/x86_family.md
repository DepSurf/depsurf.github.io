# Function: <code>x86_family</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x86_family",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595019827,
      "name": "x86_family",
      "external": false,
      "loc": "arch/x86/include/asm/microcode.h:133",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583288757,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:4",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288704,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583407413,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:4",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407360,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588264101,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:4",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264048,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588816629,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:4",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588816576,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589194757,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:4",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194704,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589436213,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:4",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589436160,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589894229,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589894176,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590120181,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590120128,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585123813,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:parse_container",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123760,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585274741,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:parse_container",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274688,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585158261,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158208,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585611109,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611056,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586767893,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767840,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595932901,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595932832,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596451157,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596451088,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597346389,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob",
        "arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd",
        "arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597346320,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589722437,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589722384,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589448213,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "drivers/edac/mce_amd.c:amd_decode_mce",
        "drivers/edac/mce_amd.c:amd_decode_mce",
        "drivers/edac/mce_amd.c:amd_decode_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589448160,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590165813,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165760,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_family(unsigned int sig)
```

```json
{
  "name": "x86_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590216325,
      "name": "x86_family",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:6",
      "file": "arch/x86/lib/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cpu.c:x86_model"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590216272,
      "name": "x86_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
unsigned int x86_family(unsigned int sig)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
unsigned int x86_family(unsigned int sig)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int x86_family(unsigned int sig)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int x86_family(unsigned int sig)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int x86_family(unsigned int sig)
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
