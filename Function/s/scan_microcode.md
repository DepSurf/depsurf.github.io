# Function: <code>scan_microcode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595020781,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:543",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595185385,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:729",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579173008,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:310",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173008,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579173120,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:322",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173120,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188016,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:327",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188016,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579199408,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:330",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579199408,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188800,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:330",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188800,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201600,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:327",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201600,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203856,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:327",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203856,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579225040,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:327",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225040,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219024,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:283",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219024,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221504,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:283",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221504,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260032,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:283",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260032,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579312016,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:269",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312016,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376784,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:143",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376784,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386320,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:143",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386320,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621666231,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:261",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob"
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202704,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:327",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202704,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137664,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:327",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137664,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203776,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:327",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203776,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```

```json
{
  "name": "scan_microcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579209056,
      "name": "scan_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:327",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209056,
      "name": "scan_microcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
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
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct microcode_intel * scan_microcode(void * data, size_t size, struct ucode_cpu_info * uci, bool save)
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
