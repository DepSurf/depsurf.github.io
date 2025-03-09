# Function: <code>x86_model</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160672,
      "name": "x86_model",
      "external": false,
      "loc": "arch/x86/include/asm/microcode.h:143",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160672,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583288752,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:17",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288752,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407408,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:17",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071583407408,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588264096,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:17",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071588264096,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588816624,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:17",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071588816624,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589194752,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:17",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071589194752,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589436208,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:17",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071589436208,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589894224,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071589894224,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590120176,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071590120176,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585123808,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches",
        "arch/x86/kernel/cpu/microcode/intel.c:microcode_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123808,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585274736,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274736,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585158256,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158256,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585611104,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611104,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586767888,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767888,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595932896,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595932896,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596451152,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596451152,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597346384,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob",
        "arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597346384,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589722432,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071589722432,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589448208,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "drivers/edac/mce_amd.c:amd_decode_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589448208,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590165808,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071590165808,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```

```json
{
  "name": "x86_model",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590216320,
      "name": "x86_model",
      "external": true,
      "loc": "arch/x86/lib/cpu.c:19",
      "file": "arch/x86/lib/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071590216320,
      "name": "x86_model",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int x86_model(unsigned int sig)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int x86_model(unsigned int sig)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int x86_model(unsigned int sig)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int x86_model(unsigned int sig)
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
