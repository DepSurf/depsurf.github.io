# Function: <code>__apply_microcode_amd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __apply_microcode_amd(struct microcode_amd * mc_amd)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579165581,
      "name": "__apply_microcode_amd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:654",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579166896,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int __apply_microcode_amd(struct microcode_amd * mc_amd)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579165792,
      "name": "__apply_microcode_amd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:666",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579165792,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __apply_microcode_amd(struct microcode_amd * mc_amd)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579177008,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:197",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177008,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579174720,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:174",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579174720,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579190096,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:174",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190096,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201824,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:174",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201824,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579190992,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:395",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190992,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203872,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:393",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203872,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206128,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:393",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206128,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229568,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:393",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229568,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220560,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:392",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220560,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223056,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:392",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223056,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579261648,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:392",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261648,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313568,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:392",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313568,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379056,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:394",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379056,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388384,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:393",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388384,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418064,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:418",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418064,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579204976,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:393",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204976,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139936,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:393",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139936,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206048,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:393",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206048,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __apply_microcode_amd(struct microcode_amd * mc)
```

```json
{
  "name": "__apply_microcode_amd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211328,
      "name": "__apply_microcode_amd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:393",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211328,
      "name": "__apply_microcode_amd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct microcode_amd * mc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct microcode_amd * mc_amd</code>
</li>
</ul>
</details>
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
int __apply_microcode_amd(struct microcode_amd * mc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __apply_microcode_amd(struct microcode_amd * mc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __apply_microcode_amd(struct microcode_amd * mc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __apply_microcode_amd(struct microcode_amd * mc)
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
