# Function: <code>microcode_sanity_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579164112,
      "name": "microcode_sanity_check",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/intel_lib.c:47",
      "file": "arch/x86/kernel/cpu/microcode/intel_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164112,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579164464,
      "name": "microcode_sanity_check",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/intel_lib.c:47",
      "file": "arch/x86/kernel/cpu/microcode/intel_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164464,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579170288,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:207",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170288,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579170112,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:219",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170112,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579185040,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:224",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185040,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:227",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196656,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    },
    {
      "addr": 18446744071579201096,
      "name": "microcode_sanity_check.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:227",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186064,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    },
    {
      "addr": 18446744071579190488,
      "name": "microcode_sanity_check.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:224",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198864,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071579203320,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:224",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201088,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071579205592,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:224",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222000,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071579226600,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:180",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216240,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071591255896,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:180",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218704,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071591199492,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:180",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257008,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071592067504,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:166",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308528,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071593833776,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:224",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579199936,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071579204440,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:224",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134928,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071579139400,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:224",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201008,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071579205512,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
```

```json
{
  "name": "microcode_sanity_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "microcode_sanity_check",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:224",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206288,
      "name": "microcode_sanity_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071579210792,
      "name": "microcode_sanity_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int microcode_sanity_check(void * mc, int print_err)
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
int microcode_sanity_check(void * mc, int print_err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int microcode_sanity_check(void * mc, int print_err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int microcode_sanity_check(void * mc, int print_err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int microcode_sanity_check(void * mc, int print_err)
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
