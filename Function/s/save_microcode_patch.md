# Function: <code>save_microcode_patch</code>

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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579171792,
      "name": "save_microcode_patch",
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
      "addr": 18446744071579171792,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579171920,
      "name": "save_microcode_patch",
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
      "addr": 18446744071579171920,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579186688,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:170",
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
      "addr": 18446744071579186688,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:170",
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
      "addr": 18446744071579198112,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071579201393,
      "name": "save_microcode_patch.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:170",
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
      "addr": 18446744071579187504,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071579190785,
      "name": "save_microcode_patch.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:167",
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
      "addr": 18446744071579200192,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071579203615,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:167",
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
      "addr": 18446744071579202416,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071579205887,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:167",
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
      "addr": 18446744071579223600,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071579226895,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(struct ucode_cpu_info * uci, void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:120",
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
      "addr": 18446744071579217568,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071591256191,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(struct ucode_cpu_info * uci, void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:120",
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
      "addr": 18446744071579220048,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071591199787,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(struct ucode_cpu_info * uci, void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:120",
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
      "addr": 18446744071579258464,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071592067856,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(struct ucode_cpu_info * uci, void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:106",
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
      "addr": 18446744071579310224,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071593834063,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(struct ucode_cpu_info * uci, void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374848,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:78",
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
      "addr": 18446744071579374848,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void save_microcode_patch(struct ucode_cpu_info * uci, void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384368,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:78",
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
      "addr": 18446744071579384368,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621666637,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:248",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:save_builtin_microcode"
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:167",
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
      "addr": 18446744071579201264,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071579204735,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:167",
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
      "addr": 18446744071579136224,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071579139698,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:167",
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
      "addr": 18446744071579202336,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071579205807,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(void * data, unsigned int size)
```

```json
{
  "name": "save_microcode_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_microcode_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:167",
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
      "addr": 18446744071579207616,
      "name": "save_microcode_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071579211087,
      "name": "save_microcode_patch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void save_microcode_patch(void * data, unsigned int size)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ucode_cpu_info * uci</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, size</code> ➡️ <code>uci, data, size</code>
</li>
</ul>
</details>
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
void save_microcode_patch(struct ucode_cpu_info * uci, void * data, unsigned int size)
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
void save_microcode_patch(void * data, unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void save_microcode_patch(void * data, unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void save_microcode_patch(void * data, unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void save_microcode_patch(void * data, unsigned int size)
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
