# Function: <code>apply_microcode_on_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579158560,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:271",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158560,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160089,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:263",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158688,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579169334,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:338",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168144,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579168719,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:378",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167936,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579182640,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:391",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579182640,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194192,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:391",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194192,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183600,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:391",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183600,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196320,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:387",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196320,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198576,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:387",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198576,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220467,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:382",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579214915,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:380",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579217379,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:380",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579255587,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:380",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579307169,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:363",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197424,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:387",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197424,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132416,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:387",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132416,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198496,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:387",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198496,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
```

```json
{
  "name": "apply_microcode_on_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203776,
      "name": "apply_microcode_on_target",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:387",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203776,
      "name": "apply_microcode_on_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int apply_microcode_on_target(int cpu)
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
int apply_microcode_on_target(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int apply_microcode_on_target(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int apply_microcode_on_target(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int apply_microcode_on_target(int cpu)
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
