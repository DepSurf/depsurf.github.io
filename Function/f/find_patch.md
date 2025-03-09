# Function: <code>find_patch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ucode_patch * find_patch(unsigned int cpu)
```

```json
{
  "name": "find_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579164768,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:541",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164768,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
struct ucode_patch * find_patch(unsigned int cpu)
```

```json
{
  "name": "find_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579165168,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:553",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579165168,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579171664,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:697",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579175024,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:568",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171664,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579175024,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579171488,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:717",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579174784,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:428",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171488,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579174784,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579186560,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:726",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579190160,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:431",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186560,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579190160,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197984,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:727",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579201888,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:431",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197984,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579201888,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579187376,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:727",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579191056,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:638",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187376,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579191056,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579200080,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:724",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579203936,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:636",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200080,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579203936,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202304,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:724",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579206192,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:636",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202304,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579206192,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223472,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:724",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579229168,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:636",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223472,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579229168,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579217440,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:681",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579222672,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:635",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217440,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579222672,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219920,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:681",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579224992,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:635",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219920,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579224992,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579258336,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:681",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579263552,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:635",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258336,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579263552,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310080,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:643",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579316128,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:641",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310080,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071579316128,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374272,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:511",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579381728,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:652",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374272,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071579381728,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383616,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:503",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579389472,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:645",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383616,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071579389472,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct ucode_patch * find_patch(unsigned int cpu)
```

```json
{
  "name": "find_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418800,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:595",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418800,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201152,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:724",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579205040,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:636",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201152,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579205040,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579136112,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:724",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579140000,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:636",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136112,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579140000,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202224,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:724",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579206112,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:636",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202224,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579206112,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```

```json
{
  "name": "find_patch",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579207504,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:724",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel"
      ]
    },
    {
      "addr": 18446744071579211392,
      "name": "find_patch",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:636",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207504,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579211392,
      "name": "find_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ucode_cpu_info * uci</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct ucode_patch *</code> ➡️ <code>struct microcode_intel *</code>
</li>
</ul>
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
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ucode_cpu_info * uci</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct microcode_intel *</code> ➡️ <code>struct ucode_patch *</code>
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
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct microcode_intel * find_patch(struct ucode_cpu_info * uci)
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
