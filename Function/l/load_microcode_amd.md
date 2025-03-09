# Function: <code>load_microcode_amd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum ucode_state load_microcode_amd(int cpu, u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579166960,
      "name": "load_microcode_amd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:853",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579166960,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 991
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
enum ucode_state load_microcode_amd(int cpu, u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579167360,
      "name": "load_microcode_amd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:863",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167360,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579176807,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:865",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579176144,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:677",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176144,
      "name": "load_microcode_amd.constprop.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 950
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579191312,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:684",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191312,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:692",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203008,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
    },
    {
      "addr": 18446744071579204741,
      "name": "load_microcode_amd.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579194290,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:840",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193296,
      "name": "load_microcode_amd.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579207141,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:838",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206144,
      "name": "load_microcode_amd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579209397,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:838",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208400,
      "name": "load_microcode_amd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579230413,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:838",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230096,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    },
    {
      "addr": 18446744071579231345,
      "name": "load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223853,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:837",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223536,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    },
    {
      "addr": 18446744071591256649,
      "name": "load_microcode_amd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579226048,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:837",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226048,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579264672,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:837",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264672,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579316720,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:843",
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
      "addr": 18446744071579316720,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
enum ucode_state load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382512,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:854",
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
      "addr": 18446744071579382512,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
enum ucode_state load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391904,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:850",
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
      "addr": 18446744071579391904,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum ucode_state load_microcode_amd(u8 family, const u8 * data, size_t size)
```

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579420336,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:823",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420336,
      "name": "load_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579208245,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:838",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207248,
      "name": "load_microcode_amd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579143093,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:838",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142096,
      "name": "load_microcode_amd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579209317,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:838",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208320,
      "name": "load_microcode_amd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579214597,
      "name": "load_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:838",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213600,
      "name": "load_microcode_amd.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
enum ucode_state load_microcode_amd(int cpu, u8 family, const u8 * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 * data, size_t size)
```
</details>
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
<b>Param removed. </b>
<code>bool save</code>
</li>
<li>
<b>Param reordered. </b>
<code>save, family, data, size</code> ➡️ <code>family, data, size</code>
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
