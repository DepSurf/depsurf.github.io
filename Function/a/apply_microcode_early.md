# Function: <code>apply_microcode_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579161824,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:647",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071579161824,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163872,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:616",
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
      "addr": 18446744071579163872,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579174496,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:575",
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
      "addr": 18446744071579174496,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579174080,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:587",
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
      "addr": 18446744071579174080,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579189408,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:583",
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
      "addr": 18446744071579189408,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:584",
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
      "addr": 18446744071579200656,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071579201557,
      "name": "apply_microcode_early.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:584",
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
      "addr": 18446744071579190048,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071579190949,
      "name": "apply_microcode_early.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:581",
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
      "addr": 18446744071579202880,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071579203823,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:581",
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
      "addr": 18446744071579205152,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071579206081,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:581",
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
      "addr": 18446744071579226160,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071579227082,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:538",
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
      "addr": 18446744071579220112,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071591256378,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:538",
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
      "addr": 18446744071579222592,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071591199974,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:538",
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
      "addr": 18446744071579260688,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071592067936,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:500",
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
      "addr": 18446744071579312512,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071593834151,
      "name": "apply_microcode_early.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579378432,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:374",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071579378432,
      "name": "apply_microcode_early.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387808,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:364",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071579387808,
      "name": "apply_microcode_early.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579417877,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:339",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:581",
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
      "addr": 18446744071579204000,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071579204929,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:581",
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
      "addr": 18446744071579138960,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071579139890,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:581",
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
      "addr": 18446744071579205072,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071579206001,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```

```json
{
  "name": "apply_microcode_early",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_microcode_early",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:581",
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
      "addr": 18446744071579210352,
      "name": "apply_microcode_early",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071579211281,
      "name": "apply_microcode_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
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
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int apply_microcode_early(struct ucode_cpu_info * uci, bool early)
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
