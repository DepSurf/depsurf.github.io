# Function: <code>collect_cpu_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579159389,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:246",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579160736,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:806",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160736,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579159544,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:238",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579160784,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:854",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160784,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579167984,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:313",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online"
      ]
    },
    {
      "addr": 18446744071579170832,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:735",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167984,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071579170832,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579167776,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:353",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online"
      ]
    },
    {
      "addr": 18446744071579170640,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:755",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167776,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071579170640,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579182480,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:370",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online"
      ]
    },
    {
      "addr": 18446744071579186048,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:764",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579182480,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071579186048,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194032,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:370",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online"
      ]
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:765",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194032,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071579197488,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071579201354,
      "name": "collect_cpu_info.cold.13",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183440,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:370",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online"
      ]
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:765",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183440,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071579186992,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071579190746,
      "name": "collect_cpu_info.cold.12",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196160,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:366",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:762",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196160,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071579199696,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071579203579,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198416,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:366",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:762",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198416,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071579201920,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071579205851,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219088,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:361",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:762",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219088,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071579223088,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071579226808,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213536,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:359",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:719",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213536,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071579217056,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071591256104,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216064,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:359",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:719",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216064,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071579219536,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071591199700,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579254288,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:359",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:719",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254288,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071579257904,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071592067769,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306720,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:342",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:681",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306720,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071579309584,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071593833966,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int collect_cpu_info(int cpu_num, struct cpu_signature * csig)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579377360,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:549",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377360,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int collect_cpu_info(int cpu_num, struct cpu_signature * csig)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386896,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:541",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386896,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int collect_cpu_info(int cpu_num, struct cpu_signature * csig)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417072,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:440",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417072,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197264,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:366",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:762",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197264,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071579200768,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071579204699,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132256,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:366",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:762",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132256,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071579135760,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071579139659,
      "name": "collect_cpu_info.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198336,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:366",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:762",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198336,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071579201840,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071579205771,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
int collect_cpu_info(int cpu)
```

```json
{
  "name": "collect_cpu_info",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203616,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:366",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "collect_cpu_info",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:762",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203616,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071579207120,
      "name": "collect_cpu_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071579211051,
      "name": "collect_cpu_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu_num</code>
</li>
<li>
<b>Param added. </b>
<code>struct cpu_signature * csig</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
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
int collect_cpu_info(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int collect_cpu_info(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int collect_cpu_info(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int collect_cpu_info(int cpu)
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
