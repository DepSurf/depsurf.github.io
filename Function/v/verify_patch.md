# Function: <code>verify_patch</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:238",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191552,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071579194917,
      "name": "verify_patch.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:236",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204416,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071579207767,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:236",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206672,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071579210023,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:236",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:parse_container"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227264,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071579231109,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:235",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:parse_container"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220768,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071591256413,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:235",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223264,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    },
    {
      "addr": 18446744071591200003,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:235",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261856,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071592068091,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:235",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314128,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071593834286,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379488,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:237",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379488,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388656,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:235",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388656,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418336,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:264",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418336,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:236",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205520,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071579208871,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:236",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140272,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071579143801,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:236",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206592,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071579209943,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```

```json
{
  "name": "verify_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:236",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211872,
      "name": "verify_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071579215223,
      "name": "verify_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```
</details>
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
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool early</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int verify_patch(u8 family, const u8 * buf, size_t buf_size, u32 * patch_size, bool early)
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
