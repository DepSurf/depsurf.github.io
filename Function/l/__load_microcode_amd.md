# Function: <code>__load_microcode_amd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579167004,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:818",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
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
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579167403,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:828",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579175664,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:829",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579175664,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 903
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579176187,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:641",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579191358,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:648",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579203073,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:656",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:805",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193520,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071579194940,
      "name": "__load_microcode_amd.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:803",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206368,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071579207790,
      "name": "__load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:803",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208624,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071579210046,
      "name": "__load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579230185,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:803",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579223625,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:802",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:802",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224400,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
    },
    {
      "addr": 18446744071591200026,
      "name": "__load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:802",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262960,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
    },
    {
      "addr": 18446744071592068114,
      "name": "__load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:808",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315312,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071593834306,
      "name": "__load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380864,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:820",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380864,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391280,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:816",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391280,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579420422,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:789",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:803",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207472,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071579208894,
      "name": "__load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:803",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142320,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071579143880,
      "name": "__load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:803",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208544,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071579209966,
      "name": "__load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "__load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:803",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213824,
      "name": "__load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071579215246,
      "name": "__load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```
</details>
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
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
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 * data, size_t size)
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
